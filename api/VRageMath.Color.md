← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Color Struct

```csharp
public struct Color: IPackedVector<uint>, IPackedVector, IEquatable<Color>
```

Represents a four-component color using red, green, blue, and alpha data.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable&lt;Color&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)  
* IPackedVector <sub>prohibited</sub>  
* IPackedVector&lt;uint&gt; <sub>prohibited</sub>

#### Fields

|Member|Description|
|---|---|
|uint PackedValue <sub>prohibited</sub>|Gets the current color as a packed value.|

#### Properties

|Member|Description|
|---|---|
|static Color AliceBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:240 G:248 B:255 A:255.|
|static Color AntiqueWhite { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:250 G:235 B:215 A:255.|
|static Color Aqua { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:255 B:255 A:255.|
|static Color Aquamarine { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:127 G:255 B:212 A:255.|
|static Color Azure { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:240 G:255 B:255 A:255.|
|static Color Beige { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:245 G:245 B:220 A:255.|
|static Color Bisque { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:228 B:196 A:255.|
|static Color Black { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:0 B:0 A:255.|
|static Color BlanchedAlmond { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:235 B:205 A:255.|
|static Color Blue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:0 B:255 A:255.|
|static Color BlueViolet { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:138 G:43 B:226 A:255.|
|static Color Brown { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:165 G:42 B:42 A:255.|
|static Color BurlyWood { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:222 G:184 B:135 A:255.|
|static Color CadetBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:95 G:158 B:160 A:255.|
|static Color Chartreuse { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:127 G:255 B:0 A:255.|
|static Color Chocolate { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:210 G:105 B:30 A:255.|
|static Color Coral { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:127 B:80 A:255.|
|static Color CornflowerBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:100 G:149 B:237 A:255.|
|static Color Cornsilk { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:248 B:220 A:255.|
|static Color Crimson { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:220 G:20 B:60 A:255.|
|static Color Cyan { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:255 B:255 A:255.|
|static Color DarkBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:0 B:139 A:255.|
|static Color DarkCyan { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:139 B:139 A:255.|
|static Color DarkGoldenrod { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:184 G:134 B:11 A:255.|
|static Color DarkGray { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:169 G:169 B:169 A:255.|
|static Color DarkGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:100 B:0 A:255.|
|static Color DarkKhaki { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:189 G:183 B:107 A:255.|
|static Color DarkMagenta { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:139 G:0 B:139 A:255.|
|static Color DarkOliveGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:85 G:107 B:47 A:255.|
|static Color DarkOrange { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:140 B:0 A:255.|
|static Color DarkOrchid { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:153 G:50 B:204 A:255.|
|static Color DarkRed { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:139 G:0 B:0 A:255.|
|static Color DarkSalmon { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:233 G:150 B:122 A:255.|
|static Color DarkSeaGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:143 G:188 B:139 A:255.|
|static Color DarkSlateBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:72 G:61 B:139 A:255.|
|static Color DarkSlateGray { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:47 G:79 B:79 A:255.|
|static Color DarkTurquoise { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:206 B:209 A:255.|
|static Color DarkViolet { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:148 G:0 B:211 A:255.|
|static Color DeepPink { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:20 B:147 A:255.|
|static Color DeepSkyBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:191 B:255 A:255.|
|static Color DimGray { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:105 G:105 B:105 A:255.|
|static Color DodgerBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:30 G:144 B:255 A:255.|
|static Color Firebrick { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:178 G:34 B:34 A:255.|
|static Color FloralWhite { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:250 B:240 A:255.|
|static Color ForestGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:34 G:139 B:34 A:255.|
|static Color Fuchsia { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:0 B:255 A:255.|
|static Color Gainsboro { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:220 G:220 B:220 A:255.|
|static Color GhostWhite { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:248 G:248 B:255 A:255.|
|static Color Gold { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:215 B:0 A:255.|
|static Color Goldenrod { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:218 G:165 B:32 A:255.|
|static Color Gray { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:128 G:128 B:128 A:255.|
|static Color Green { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:128 B:0 A:255.|
|static Color GreenYellow { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:173 G:255 B:47 A:255.|
|static Color Honeydew { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:240 G:255 B:240 A:255.|
|static Color HotPink { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:105 B:180 A:255.|
|static Color IndianRed { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:205 G:92 B:92 A:255.|
|static Color Indigo { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:75 G:0 B:130 A:255.|
|static Color Ivory { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:255 B:240 A:255.|
|static Color Khaki { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:240 G:230 B:140 A:255.|
|static Color Lavender { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:230 G:230 B:250 A:255.|
|static Color LavenderBlush { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:240 B:245 A:255.|
|static Color LawnGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:124 G:252 B:0 A:255.|
|static Color LemonChiffon { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:250 B:205 A:255.|
|static Color LightBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:173 G:216 B:230 A:255.|
|static Color LightCoral { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:240 G:128 B:128 A:255.|
|static Color LightCyan { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:224 G:255 B:255 A:255.|
|static Color LightGoldenrodYellow { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:250 G:250 B:210 A:255.|
|static Color LightGray { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:211 G:211 B:211 A:255.|
|static Color LightGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:144 G:238 B:144 A:255.|
|static Color LightPink { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:182 B:193 A:255.|
|static Color LightSalmon { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:160 B:122 A:255.|
|static Color LightSeaGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:32 G:178 B:170 A:255.|
|static Color LightSkyBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:135 G:206 B:250 A:255.|
|static Color LightSlateGray { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:119 G:136 B:153 A:255.|
|static Color LightSteelBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:176 G:196 B:222 A:255.|
|static Color LightYellow { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:255 B:224 A:255.|
|static Color Lime { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:255 B:0 A:255.|
|static Color LimeGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:50 G:205 B:50 A:255.|
|static Color Linen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:250 G:240 B:230 A:255.|
|static Color Magenta { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:0 B:255 A:255.|
|static Color Maroon { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:128 G:0 B:0 A:255.|
|static Color MediumAquamarine { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:102 G:205 B:170 A:255.|
|static Color MediumBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:0 B:205 A:255.|
|static Color MediumOrchid { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:186 G:85 B:211 A:255.|
|static Color MediumPurple { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:147 G:112 B:219 A:255.|
|static Color MediumSeaGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:60 G:179 B:113 A:255.|
|static Color MediumSlateBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:123 G:104 B:238 A:255.|
|static Color MediumSpringGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:250 B:154 A:255.|
|static Color MediumTurquoise { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:72 G:209 B:204 A:255.|
|static Color MediumVioletRed { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:199 G:21 B:133 A:255.|
|static Color MidnightBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:25 G:25 B:112 A:255.|
|static Color MintCream { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:245 G:255 B:250 A:255.|
|static Color MistyRose { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:228 B:225 A:255.|
|static Color Moccasin { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:228 B:181 A:255.|
|static Color NavajoWhite { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:222 B:173 A:255.|
|static Color Navy { get; } <sub>prohibited</sub>|Gets a system-defined color R:0 G:0 B:128 A:255.|
|static Color OldLace { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:253 G:245 B:230 A:255.|
|static Color Olive { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:128 G:128 B:0 A:255.|
|static Color OliveDrab { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:107 G:142 B:35 A:255.|
|static Color Orange { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:165 B:0 A:255.|
|static Color OrangeRed { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:69 B:0 A:255.|
|static Color Orchid { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:218 G:112 B:214 A:255.|
|static Color PaleGoldenrod { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:238 G:232 B:170 A:255.|
|static Color PaleGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:152 G:251 B:152 A:255.|
|static Color PaleTurquoise { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:175 G:238 B:238 A:255.|
|static Color PaleVioletRed { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:219 G:112 B:147 A:255.|
|static Color PapayaWhip { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:239 B:213 A:255.|
|static Color PeachPuff { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:218 B:185 A:255.|
|static Color Peru { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:205 G:133 B:63 A:255.|
|static Color Pink { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:192 B:203 A:255.|
|static Color Plum { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:221 G:160 B:221 A:255.|
|static Color PowderBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:176 G:224 B:230 A:255.|
|static Color Purple { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:128 G:0 B:128 A:255.|
|static Color Red { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:0 B:0 A:255.|
|static Color RosyBrown { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:188 G:143 B:143 A:255.|
|static Color RoyalBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:65 G:105 B:225 A:255.|
|static Color SaddleBrown { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:139 G:69 B:19 A:255.|
|static Color Salmon { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:250 G:128 B:114 A:255.|
|static Color SandyBrown { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:244 G:164 B:96 A:255.|
|static Color SeaGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:46 G:139 B:87 A:255.|
|static Color SeaShell { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:245 B:238 A:255.|
|static Color Sienna { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:160 G:82 B:45 A:255.|
|static Color Silver { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:192 G:192 B:192 A:255.|
|static Color SkyBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:135 G:206 B:235 A:255.|
|static Color SlateBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:106 G:90 B:205 A:255.|
|static Color SlateGray { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:112 G:128 B:144 A:255.|
|static Color Snow { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:250 B:250 A:255.|
|static Color SpringGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:255 B:127 A:255.|
|static Color SteelBlue { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:70 G:130 B:180 A:255.|
|static Color Tan { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:210 G:180 B:140 A:255.|
|static Color Teal { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:128 B:128 A:255.|
|static Color Thistle { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:216 G:191 B:216 A:255.|
|static Color Tomato { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:99 B:71 A:255.|
|static Color Transparent { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:0 G:0 B:0 A:0.|
|static Color Turquoise { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:64 G:224 B:208 A:255.|
|static Color Violet { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:238 G:130 B:238 A:255.|
|static Color Wheat { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:245 G:222 B:179 A:255.|
|static Color White { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:255 B:255 A:255.|
|static Color WhiteSmoke { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:245 G:245 B:245 A:255.|
|static Color Yellow { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:255 G:255 B:0 A:255.|
|static Color YellowGreen { get; } <sub>prohibited</sub>|Gets a system-defined color with the value R:154 G:205 B:50 A:255.|
|byte A { get; set; } <sub>prohibited</sub>|Gets or sets the alpha component value.|
|byte B { get; set; } <sub>prohibited</sub>|Gets or sets the blue component value of this Color.|
|byte G { get; set; } <sub>prohibited</sub>|Gets or sets the green component value of this Color.|
|byte R { get; set; } <sub>prohibited</sub>|Gets or sets the red component value of this Color.|
|byte X { get; set; } <sub>prohibited</sub>|Gets or sets the red component value of this Color.|
|byte Y { get; set; } <sub>prohibited</sub>|Gets or sets the green component value of this Color.|
|byte Z { get; set; } <sub>prohibited</sub>|Gets or sets the blue component value of this Color.|

#### Constructors

|Member|Description|
|---|---|
|Color(uint) <sub>prohibited</sub>||
|Color(int, int, int) <sub>prohibited</sub>||
|Color(int, int, int, int) <sub>prohibited</sub>||
|Color(float) <sub>prohibited</sub>||
|Color(float, float, float) <sub>prohibited</sub>||
|Color(float, float, float, float) <sub>prohibited</sub>||
|Color(Color, float) <sub>prohibited</sub>||
|Color(Vector3) <sub>prohibited</sub>||
|Color(Vector4) <sub>prohibited</sub>||

#### Methods

|Member|Description|
|---|---|
|static Color Darken(Color, double) <sub>prohibited</sub>||
|static Color FromNonPremultiplied(Vector4) <sub>prohibited</sub>|Convert a non premultipled color into color data that contains alpha.|
|static Color FromNonPremultiplied(int, int, int, int) <sub>prohibited</sub>|Converts a non-premultipled alpha color to a color that contains premultiplied alpha.|
|static Color Lerp(Color, Color, float) <sub>prohibited</sub>|Linearly interpolate a color.|
|static Color Lighten(Color, double) <sub>prohibited</sub>||
|static Color Multiply(Color, float) <sub>prohibited</sub>|Multiply each color component by the scale factor.|
|bool Equals(object) <sub>prohibited</sub>|Test an instance of a color object to see if it is equal to this object.|
|bool Equals(Color) <sub>prohibited</sub>|Test a color to see if it is equal to the color in this instance.|
|int GetHashCode() <sub>prohibited</sub>|Serves as a hash function for a particular type.|
|Color ToGray() <sub>prohibited</sub>||
|string ToString() <sub>prohibited</sub>|Gets a string representation of this object.|
|Vector3 ToVector3() <sub>prohibited</sub>|Gets a three-component vector representation for this object.|
|Vector4 ToVector4() <sub>prohibited</sub>|Gets a four-component vector representation for this object.|

