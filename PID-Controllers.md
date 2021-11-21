__[TOC]__

# 1. What is a PID Controller?

A PID (Proportional Integral Derivative) controller is a control loop mechanism that allows you to easily reduce the error of a system using 3 different terms:
* Proportional term
* Integral term
* Derivative term

The lovely thing about PID controllers is that you can pretty effectively control a very complex system _without_ needing to characterize the full dynamic behavior of the system. There is a whole branch of engineering dedicated to control characterization and optimization, but I'm not going to dig into that because not much of it is beyond the scope of what is practically useful in SE (and a lot of it is magic). What this article seeks to do is give users a solid general understanding of how the internals of a PID controller work and provide several example use cases where they would be helpful.

## 1.1. Breaking it Down

As mentioned above, a PID can be broken into 3 different parts: Proportion, Integral, and Derivative. Each term has an associated constant or **gain** that is used to control how strong the response is for that term. For example, if you have a PID controller with P gain as 1, I gain as 0, and D gain as 0, then only the proportional term will be used. 

The basic algorithm of a PID controller looks like the following:

```
[PID Output] = [Proportional Term] + [Integral Term] + [Derivative Term]

But what does each of these terms mean/do?

### 1.1.1 The Proportional Term

The Proportional term dictates how _fast_ your controller will seek to cancel out error. You can think of it as the "speed" of your response. This is the simplest term to understand and tune since it simply scales the error by a constant number. If you set this too low, you will control very slowly. If you set this too high, the system will oscillate.

```
[Proportional Term] = [Proportional Constant] * [Current Error]
```

### 1.1.2 The Integral Term

The Integral term changes how your controller responds to persistent errors. This term serves sort of like "memory" of the previous errors to try and prevent future errors.

```
[Error Integral] = [Last Error Integral] + [Current Error] * [Time Step]
[Integral Term] = [Integral Constant] * [Error Integral]
```

### 1.1.3 The Derivative Term

The Derivative term changes how your controller responds to the speed of the error change. You can think of this like a _dampening_ term to a certain extent because we can use it to cancel out oscillations caused by large P terms.

```
[Error Derivative] = ( [Current Error] - [Last Error] ) / [Time Step]
[Derivative Term] = [Derivative Constant] * [Error Derivative]
```