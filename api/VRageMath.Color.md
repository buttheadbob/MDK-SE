← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Color Struct

```csharp
public struct Color: IPackedVector<System.UInt32>, IPackedVector, IEquatable<VRageMath.Color>
```

Represents a four-component color using red, green, blue, and alpha data.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IPackedVector<System.UInt32>](VRageMath.PackedVector.IPackedVector`1[[System.UInt32, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089]])  
* [IPackedVector](VRageMath.PackedVector.IPackedVector)  
* [IEquatable<VRageMath.Color>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|PackedValue|Gets the current color as a packed value.|

#### Properties

|Member|Description|
|---|---|
|X { get; set; }|Gets or sets the red component value of this Color.|
|Y { get; set; }|Gets or sets the green component value of this Color.|
|Z { get; set; }|Gets or sets the blue component value of this Color.|
|R { get; set; }|Gets or sets the red component value of this Color.|
|G { get; set; }|Gets or sets the green component value of this Color.|
|B { get; set; }|Gets or sets the blue component value of this Color.|
|A { get; set; }|Gets or sets the alpha component value.|
|Transparent { get; }|Gets a system-defined color with the value R:0 G:0 B:0 A:0.|
|AliceBlue { get; }|Gets a system-defined color with the value R:240 G:248 B:255 A:255.|
|AntiqueWhite { get; }|Gets a system-defined color with the value R:250 G:235 B:215 A:255.|
|Aqua { get; }|Gets a system-defined color with the value R:0 G:255 B:255 A:255.|
|Aquamarine { get; }|Gets a system-defined color with the value R:127 G:255 B:212 A:255.|
|Azure { get; }|Gets a system-defined color with the value R:240 G:255 B:255 A:255.|
|Beige { get; }|Gets a system-defined color with the value R:245 G:245 B:220 A:255.|
|Bisque { get; }|Gets a system-defined color with the value R:255 G:228 B:196 A:255.|
|Black { get; }|Gets a system-defined color with the value R:0 G:0 B:0 A:255.|
|BlanchedAlmond { get; }|Gets a system-defined color with the value R:255 G:235 B:205 A:255.|
|Blue { get; }|Gets a system-defined color with the value R:0 G:0 B:255 A:255.|
|BlueViolet { get; }|Gets a system-defined color with the value R:138 G:43 B:226 A:255.|
|Brown { get; }|Gets a system-defined color with the value R:165 G:42 B:42 A:255.|
|BurlyWood { get; }|Gets a system-defined color with the value R:222 G:184 B:135 A:255.|
|CadetBlue { get; }|Gets a system-defined color with the value R:95 G:158 B:160 A:255.|
|Chartreuse { get; }|Gets a system-defined color with the value R:127 G:255 B:0 A:255.|
|Chocolate { get; }|Gets a system-defined color with the value R:210 G:105 B:30 A:255.|
|Coral { get; }|Gets a system-defined color with the value R:255 G:127 B:80 A:255.|
|CornflowerBlue { get; }|Gets a system-defined color with the value R:100 G:149 B:237 A:255.|
|Cornsilk { get; }|Gets a system-defined color with the value R:255 G:248 B:220 A:255.|
|Crimson { get; }|Gets a system-defined color with the value R:220 G:20 B:60 A:255.|
|Cyan { get; }|Gets a system-defined color with the value R:0 G:255 B:255 A:255.|
|DarkBlue { get; }|Gets a system-defined color with the value R:0 G:0 B:139 A:255.|
|DarkCyan { get; }|Gets a system-defined color with the value R:0 G:139 B:139 A:255.|
|DarkGoldenrod { get; }|Gets a system-defined color with the value R:184 G:134 B:11 A:255.|
|DarkGray { get; }|Gets a system-defined color with the value R:169 G:169 B:169 A:255.|
|DarkGreen { get; }|Gets a system-defined color with the value R:0 G:100 B:0 A:255.|
|DarkKhaki { get; }|Gets a system-defined color with the value R:189 G:183 B:107 A:255.|
|DarkMagenta { get; }|Gets a system-defined color with the value R:139 G:0 B:139 A:255.|
|DarkOliveGreen { get; }|Gets a system-defined color with the value R:85 G:107 B:47 A:255.|
|DarkOrange { get; }|Gets a system-defined color with the value R:255 G:140 B:0 A:255.|
|DarkOrchid { get; }|Gets a system-defined color with the value R:153 G:50 B:204 A:255.|
|DarkRed { get; }|Gets a system-defined color with the value R:139 G:0 B:0 A:255.|
|DarkSalmon { get; }|Gets a system-defined color with the value R:233 G:150 B:122 A:255.|
|DarkSeaGreen { get; }|Gets a system-defined color with the value R:143 G:188 B:139 A:255.|
|DarkSlateBlue { get; }|Gets a system-defined color with the value R:72 G:61 B:139 A:255.|
|DarkSlateGray { get; }|Gets a system-defined color with the value R:47 G:79 B:79 A:255.|
|DarkTurquoise { get; }|Gets a system-defined color with the value R:0 G:206 B:209 A:255.|
|DarkViolet { get; }|Gets a system-defined color with the value R:148 G:0 B:211 A:255.|
|DeepPink { get; }|Gets a system-defined color with the value R:255 G:20 B:147 A:255.|
|DeepSkyBlue { get; }|Gets a system-defined color with the value R:0 G:191 B:255 A:255.|
|DimGray { get; }|Gets a system-defined color with the value R:105 G:105 B:105 A:255.|
|DodgerBlue { get; }|Gets a system-defined color with the value R:30 G:144 B:255 A:255.|
|Firebrick { get; }|Gets a system-defined color with the value R:178 G:34 B:34 A:255.|
|FloralWhite { get; }|Gets a system-defined color with the value R:255 G:250 B:240 A:255.|
|ForestGreen { get; }|Gets a system-defined color with the value R:34 G:139 B:34 A:255.|
|Fuchsia { get; }|Gets a system-defined color with the value R:255 G:0 B:255 A:255.|
|Gainsboro { get; }|Gets a system-defined color with the value R:220 G:220 B:220 A:255.|
|GhostWhite { get; }|Gets a system-defined color with the value R:248 G:248 B:255 A:255.|
|Gold { get; }|Gets a system-defined color with the value R:255 G:215 B:0 A:255.|
|Goldenrod { get; }|Gets a system-defined color with the value R:218 G:165 B:32 A:255.|
|Gray { get; }|Gets a system-defined color with the value R:128 G:128 B:128 A:255.|
|Green { get; }|Gets a system-defined color with the value R:0 G:128 B:0 A:255.|
|GreenYellow { get; }|Gets a system-defined color with the value R:173 G:255 B:47 A:255.|
|Honeydew { get; }|Gets a system-defined color with the value R:240 G:255 B:240 A:255.|
|HotPink { get; }|Gets a system-defined color with the value R:255 G:105 B:180 A:255.|
|IndianRed { get; }|Gets a system-defined color with the value R:205 G:92 B:92 A:255.|
|Indigo { get; }|Gets a system-defined color with the value R:75 G:0 B:130 A:255.|
|Ivory { get; }|Gets a system-defined color with the value R:255 G:255 B:240 A:255.|
|Khaki { get; }|Gets a system-defined color with the value R:240 G:230 B:140 A:255.|
|Lavender { get; }|Gets a system-defined color with the value R:230 G:230 B:250 A:255.|
|LavenderBlush { get; }|Gets a system-defined color with the value R:255 G:240 B:245 A:255.|
|LawnGreen { get; }|Gets a system-defined color with the value R:124 G:252 B:0 A:255.|
|LemonChiffon { get; }|Gets a system-defined color with the value R:255 G:250 B:205 A:255.|
|LightBlue { get; }|Gets a system-defined color with the value R:173 G:216 B:230 A:255.|
|LightCoral { get; }|Gets a system-defined color with the value R:240 G:128 B:128 A:255.|
|LightCyan { get; }|Gets a system-defined color with the value R:224 G:255 B:255 A:255.|
|LightGoldenrodYellow { get; }|Gets a system-defined color with the value R:250 G:250 B:210 A:255.|
|LightGreen { get; }|Gets a system-defined color with the value R:144 G:238 B:144 A:255.|
|LightGray { get; }|Gets a system-defined color with the value R:211 G:211 B:211 A:255.|
|LightPink { get; }|Gets a system-defined color with the value R:255 G:182 B:193 A:255.|
|LightSalmon { get; }|Gets a system-defined color with the value R:255 G:160 B:122 A:255.|
|LightSeaGreen { get; }|Gets a system-defined color with the value R:32 G:178 B:170 A:255.|
|LightSkyBlue { get; }|Gets a system-defined color with the value R:135 G:206 B:250 A:255.|
|LightSlateGray { get; }|Gets a system-defined color with the value R:119 G:136 B:153 A:255.|
|LightSteelBlue { get; }|Gets a system-defined color with the value R:176 G:196 B:222 A:255.|
|LightYellow { get; }|Gets a system-defined color with the value R:255 G:255 B:224 A:255.|
|Lime { get; }|Gets a system-defined color with the value R:0 G:255 B:0 A:255.|
|LimeGreen { get; }|Gets a system-defined color with the value R:50 G:205 B:50 A:255.|
|Linen { get; }|Gets a system-defined color with the value R:250 G:240 B:230 A:255.|
|Magenta { get; }|Gets a system-defined color with the value R:255 G:0 B:255 A:255.|
|Maroon { get; }|Gets a system-defined color with the value R:128 G:0 B:0 A:255.|
|MediumAquamarine { get; }|Gets a system-defined color with the value R:102 G:205 B:170 A:255.|
|MediumBlue { get; }|Gets a system-defined color with the value R:0 G:0 B:205 A:255.|
|MediumOrchid { get; }|Gets a system-defined color with the value R:186 G:85 B:211 A:255.|
|MediumPurple { get; }|Gets a system-defined color with the value R:147 G:112 B:219 A:255.|
|MediumSeaGreen { get; }|Gets a system-defined color with the value R:60 G:179 B:113 A:255.|
|MediumSlateBlue { get; }|Gets a system-defined color with the value R:123 G:104 B:238 A:255.|
|MediumSpringGreen { get; }|Gets a system-defined color with the value R:0 G:250 B:154 A:255.|
|MediumTurquoise { get; }|Gets a system-defined color with the value R:72 G:209 B:204 A:255.|
|MediumVioletRed { get; }|Gets a system-defined color with the value R:199 G:21 B:133 A:255.|
|MidnightBlue { get; }|Gets a system-defined color with the value R:25 G:25 B:112 A:255.|
|MintCream { get; }|Gets a system-defined color with the value R:245 G:255 B:250 A:255.|
|MistyRose { get; }|Gets a system-defined color with the value R:255 G:228 B:225 A:255.|
|Moccasin { get; }|Gets a system-defined color with the value R:255 G:228 B:181 A:255.|
|NavajoWhite { get; }|Gets a system-defined color with the value R:255 G:222 B:173 A:255.|
|Navy { get; }|Gets a system-defined color R:0 G:0 B:128 A:255.|
|OldLace { get; }|Gets a system-defined color with the value R:253 G:245 B:230 A:255.|
|Olive { get; }|Gets a system-defined color with the value R:128 G:128 B:0 A:255.|
|OliveDrab { get; }|Gets a system-defined color with the value R:107 G:142 B:35 A:255.|
|Orange { get; }|Gets a system-defined color with the value R:255 G:165 B:0 A:255.|
|OrangeRed { get; }|Gets a system-defined color with the value R:255 G:69 B:0 A:255.|
|Orchid { get; }|Gets a system-defined color with the value R:218 G:112 B:214 A:255.|
|PaleGoldenrod { get; }|Gets a system-defined color with the value R:238 G:232 B:170 A:255.|
|PaleGreen { get; }|Gets a system-defined color with the value R:152 G:251 B:152 A:255.|
|PaleTurquoise { get; }|Gets a system-defined color with the value R:175 G:238 B:238 A:255.|
|PaleVioletRed { get; }|Gets a system-defined color with the value R:219 G:112 B:147 A:255.|
|PapayaWhip { get; }|Gets a system-defined color with the value R:255 G:239 B:213 A:255.|
|PeachPuff { get; }|Gets a system-defined color with the value R:255 G:218 B:185 A:255.|
|Peru { get; }|Gets a system-defined color with the value R:205 G:133 B:63 A:255.|
|Pink { get; }|Gets a system-defined color with the value R:255 G:192 B:203 A:255.|
|Plum { get; }|Gets a system-defined color with the value R:221 G:160 B:221 A:255.|
|PowderBlue { get; }|Gets a system-defined color with the value R:176 G:224 B:230 A:255.|
|Purple { get; }|Gets a system-defined color with the value R:128 G:0 B:128 A:255.|
|Red { get; }|Gets a system-defined color with the value R:255 G:0 B:0 A:255.|
|RosyBrown { get; }|Gets a system-defined color with the value R:188 G:143 B:143 A:255.|
|RoyalBlue { get; }|Gets a system-defined color with the value R:65 G:105 B:225 A:255.|
|SaddleBrown { get; }|Gets a system-defined color with the value R:139 G:69 B:19 A:255.|
|Salmon { get; }|Gets a system-defined color with the value R:250 G:128 B:114 A:255.|
|SandyBrown { get; }|Gets a system-defined color with the value R:244 G:164 B:96 A:255.|
|SeaGreen { get; }|Gets a system-defined color with the value R:46 G:139 B:87 A:255.|
|SeaShell { get; }|Gets a system-defined color with the value R:255 G:245 B:238 A:255.|
|Sienna { get; }|Gets a system-defined color with the value R:160 G:82 B:45 A:255.|
|Silver { get; }|Gets a system-defined color with the value R:192 G:192 B:192 A:255.|
|SkyBlue { get; }|Gets a system-defined color with the value R:135 G:206 B:235 A:255.|
|SlateBlue { get; }|Gets a system-defined color with the value R:106 G:90 B:205 A:255.|
|SlateGray { get; }|Gets a system-defined color with the value R:112 G:128 B:144 A:255.|
|Snow { get; }|Gets a system-defined color with the value R:255 G:250 B:250 A:255.|
|SpringGreen { get; }|Gets a system-defined color with the value R:0 G:255 B:127 A:255.|
|SteelBlue { get; }|Gets a system-defined color with the value R:70 G:130 B:180 A:255.|
|Tan { get; }|Gets a system-defined color with the value R:210 G:180 B:140 A:255.|
|Teal { get; }|Gets a system-defined color with the value R:0 G:128 B:128 A:255.|
|Thistle { get; }|Gets a system-defined color with the value R:216 G:191 B:216 A:255.|
|Tomato { get; }|Gets a system-defined color with the value R:255 G:99 B:71 A:255.|
|Turquoise { get; }|Gets a system-defined color with the value R:64 G:224 B:208 A:255.|
|Violet { get; }|Gets a system-defined color with the value R:238 G:130 B:238 A:255.|
|Wheat { get; }|Gets a system-defined color with the value R:245 G:222 B:179 A:255.|
|White { get; }|Gets a system-defined color with the value R:255 G:255 B:255 A:255.|
|WhiteSmoke { get; }|Gets a system-defined color with the value R:245 G:245 B:245 A:255.|
|Yellow { get; }|Gets a system-defined color with the value R:255 G:255 B:0 A:255.|
|YellowGreen { get; }|Gets a system-defined color with the value R:154 G:205 B:50 A:255.|

#### Constructors

|Member|Description|
|---|---|
|Color(uint)||
|Color(int, int, int)||
|Color(int, int, int, int)||
|Color(float)||
|Color(float, float, float)||
|Color(float, float, float, float)||
|Color(Color, float)||
|Color(Vector3)||
|Color(Vector4)||

#### Methods

|Member|Description|
|---|---|
|FromNonPremultiplied(Vector4)|Convert a non premultipled color into color data that contains alpha.|
|FromNonPremultiplied(int, int, int, int)|Converts a non-premultipled alpha color to a color that contains premultiplied alpha.|
|ToVector3()|Gets a three-component vector representation for this object.|
|ToVector4()|Gets a four-component vector representation for this object.|
|Lerp(Color, Color, float)|Linearly interpolate a color.|
|Multiply(Color, float)|Multiply each color component by the scale factor.|
|ToString()|Gets a string representation of this object.|
|GetHashCode()|Serves as a hash function for a particular type.|
|Equals(object)|Test an instance of a color object to see if it is equal to this object.|
|Equals(Color)|Test a color to see if it is equal to the color in this instance.|
|Lighten(Color, double)||
|Darken(Color, double)||
|ToGray()||

