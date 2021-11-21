# Table of Contents

* [1. What is a PID Controller?](#1-what-is-a-pid-controller)
* [2. PID Controller Applications](#2-pid-controller-applications)
* [3. Breaking it Down](#3-breaking-it-down)
    * [3.1 The Proportional Term](#31-the-proportional-term)
    * [3.1 The Integral Term](#32-the-integral-term)
    * [3.1 The Derivative Term](#33-the-derivative-term)
* [4. PID Tuning](#4-pid-tuning)
* [5. Example Implementation](#5-example-implementation)

***

# 1. What is a PID Controller?

A PID (Proportional Integral Derivative) controller is a control loop mechanism that allows you to easily reduce the error of a system using 3 different terms:
* Proportional term
* Integral term
* Derivative term

The lovely thing about PID controllers is that you can pretty effectively control a very complex system **without** needing to characterize the full dynamic behavior of the system. PIDs are _reactive_ in nature since they have no knowledge of the process you are trying to control, so they are not the mathematically optimal way to control systems. However, PIDs are incredibly easy to implement, and they handle the problem _well enough_ for many applications; their utility is undeniable.

There is a whole branch of engineering dedicated to control characterization and optimization, but I'm not going to dig into that because not much of it is beyond the scope of what is practically useful in SE (and a lot of it is magic). What this article seeks to do is give users a solid general understanding of how the internals of a PID controller work and give you the tools to effectively utilize them.

# 2. PID Controller Applications

You could use PID controllers for many things like:

* Controlling gyros to point your ship in a certain direction
* Controlling the thrust of a ship to make a cruise control
* Extending/retracting a piston to a certain position
* Rotating a rotor to a certain angle

PID controllers are incredibly powerful tools once we learn how to use them!

# 3. Breaking it Down

As mentioned above, a PID can be broken into 3 different parts: Proportionl, Integral, and Derivative. Each term has an associated constant or **gain** that is used to control how strong the response is for that term. For example, if you have a PID controller with P gain as 1, I gain as 0, and D gain as 0, then only the proportional term will be used. 

The basic algorithm of a PID controller looks like the following:

```
[PID Output] = [Proportional Term] + [Integral Term] + [Derivative Term]
```

But what does each of these terms mean/do?

## 3.1 The Proportional Term

The Proportional term dictates how _fast_ your controller will seek to cancel out error. You can think of it as the "speed" of your response. This is the simplest term to understand and tune since it simply scales the error by a constant number. If you set this too low, you will control very slowly. If you set this too high, the system will oscillate.

```
[Proportional Term] = [Proportional Constant] * [Current Error]
```

## 3.2 The Integral Term

The Integral term changes how your controller responds to persistent errors. This term serves sort of like "memory" of the previous errors to try and prevent future errors. Do note that if the integral gain is too large, this can cause large oscillations.

```
[Error Integral] = [Last Error Integral] + [Current Error] * [Time Step]
[Integral Term] = [Integral Constant] * [Error Integral]
```

## 3.3 The Derivative Term

The Derivative term changes how your controller responds to the speed of the error change. You can think of this like a _dampening_ term as it tries to _predict_ the behavior of the system and can be used reduce oscillations.

```
[Error Derivative] = ( [Current Error] - [Last Error] ) / [Time Step]
[Derivative Term] = [Derivative Constant] * [Error Derivative]
```

## 4. PID Tuning

The way that we get our PIDs to behave the way we want is via _tuning_. Tuning can be manual or even automatic, but for the purposes of this guide, I will focus on manual tuning since that is the easiest.

The general tuning process that I recommend is the following:

0. Initialize the PID constants to 1,0,0 respectively (only unit gain proportional control).
1. Increase the P gain.
2. Increase the I gain if there is any persistent steady-state error. Otherwise, you can leave this at 0.
3. Increase the D gain to reduce oscillations. Increase this in small amounts though, as the D term is notoriously twitchy.
4. Repeat steps (1-3) until you are satisfied with the behavior.

It is worth noting though, that if speed is not that big of a concern, a simple P controller (a PID with I and D gains set to 0) will suffice. In that event, simply complete steps 0-1 and set the P gain to where it is fast, but doesn't oscillate.

# 5. Example Implementation

There are many ways to implement a PID controller in code, but this is my implementation that I use in most of my scripts.

There are 4 classes in this implementation:

* `PID`: The most basic PID controller. Does nothing fancy, just a bare bones implementation.
* `DecayingIntegralPID`: A PID controller where the error integral decays over time so that it does not accumulate too much.
* `ClampedIntegralPID`: A PID controller that caps the minimum and maximum error integral value.
* `BufferedIntegralPID`: A PID that uses a fixed length buffer to compute the error integral from.

Due to the tendency for high error integrals to cause oscillations, the latter 3 classes try to limit that integral in different ways for better transient behavior. Out of all of these, I like the `DecayingIntegralPID` the most, but you can experiment and see which you like best!

<details>
<summary>
(Click to Expand)
</summary>

```cs
#region PID Class

/// <summary>
/// Discrete time PID controller class.
/// (Whiplash141 - 11/22/2018)
/// </summary>
public class PID
{
	readonly double _kP = 0;
	readonly double _kI = 0;
	readonly double _kD = 0;
	
	double _timeStep = 0;
	double _inverseTimeStep = 0;
	double _errorSum = 0;
	double _lastError = 0;
	bool _firstRun = true;
	
	public double Value { get; private set; }

	public PID(double kP, double kI, double kD, double timeStep)
	{
		_kP = kP;
		_kI = kI;
		_kD = kD;
		_timeStep = timeStep;
		_inverseTimeStep = 1 / _timeStep;
	}

	protected virtual double GetIntegral(double currentError, double errorSum, double timeStep)
	{
		return errorSum + currentError * timeStep;
	}

	public double Control(double error)
	{
		//Compute derivative term
		var errorDerivative = (error - _lastError) * _inverseTimeStep;

		if (_firstRun)
		{
			errorDerivative = 0;
			_firstRun = false;
		}

		//Get error sum
		_errorSum = GetIntegral(error, _errorSum, _timeStep);

		//Store this error as last error
		_lastError = error;

		//Construct output
		this.Value = _kP * error + _kI * _errorSum + _kD * errorDerivative;
		return this.Value;
	}

	public double Control(double error, double timeStep)
	{
		if (timeStep != _timeStep)
		{
			_timeStep = timeStep;
			_inverseTimeStep = 1 / _timeStep;
		}
		return Control(error);
	}

	public void Reset()
	{
		_errorSum = 0;
		_lastError = 0;
		_firstRun = true;
	}
}

public class DecayingIntegralPID : PID
{
	readonly double _decayRatio;

	public DecayingIntegralPID(double kP, double kI, double kD, double timeStep, double decayRatio) : base(kP, kI, kD, timeStep)
	{
		_decayRatio = decayRatio;
	}

	protected override double GetIntegral(double currentError, double errorSum, double timeStep)
	{
		return errorSum = errorSum * (1.0 - _decayRatio) + currentError * timeStep;
	}
}

public class ClampedIntegralPID : PID
{
	readonly double _upperBound;
	readonly double _lowerBound;

	public ClampedIntegralPID(double kP, double kI, double kD, double timeStep, double lowerBound, double upperBound) : base (kP, kI, kD, timeStep)
	{
		_upperBound = upperBound;
		_lowerBound = lowerBound;
	}

	protected override double GetIntegral(double currentError, double errorSum, double timeStep)
	{
		errorSum = errorSum + currentError * timeStep;
		return Math.Min(_upperBound, Math.Max(errorSum, _lowerBound));
	}
}

public class BufferedIntegralPID : PID
{
	readonly Queue<double> _integralBuffer = new Queue<double>();
	readonly int _bufferSize = 0;

	public BufferedIntegralPID(double kP, double kI, double kD, double timeStep, int bufferSize) : base(kP, kI, kD, timeStep)
	{
		_bufferSize = bufferSize;
	}

	protected override double GetIntegral(double currentError, double errorSum, double timeStep)
	{
		if (_integralBuffer.Count == _bufferSize)
			_integralBuffer.Dequeue();
		_integralBuffer.Enqueue(currentError * timeStep);
		return _integralBuffer.Sum();
	}
}

#endregion
```

</details>



***


_A big thank you goes to Whiplash141 for writing this tutorial._
