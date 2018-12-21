← [Index](index)
# ColorExtensions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Methods
|Member|Description|
|---|---|
|static [`Vector3 ColorToHSV(Color rgb)`](VRageMath.ColorToHSV)||
|static [`Vector3 ColorToHSVDX11(Color rgb)`](VRageMath.ColorToHSVDX11)|Use this for HSV in DX11 Renderer, X = Hue 0..1, Y = Saturation -1..1, Z = Value -1..1|
|static [`Color HexToColor(string hex)`](VRageMath.HexToColor)||
|static [`Vector4 HexToVector4(string hex)`](VRageMath.HexToVector4)||
|static [`Color HSVtoColor(Vector3 HSV)`](VRageMath.HSVtoColor)||
|static [`uint PackHSVToUint(Vector3 HSV)`](VRageMath.PackHSVToUint)||
|static [`Vector3 UnpackHSVFromUint(uint packed)`](VRageMath.UnpackHSVFromUint)||
|static [`float HueDistance(Color color, float hue)`](VRageMath.HueDistance)||
|static [`float HueDistance(Color color, Color otherColor)`](VRageMath.HueDistance)||
|static [`Vector3 TemperatureToRGB(float temperature)`](VRageMath.TemperatureToRGB)||
|static [`Vector4 UnmultiplyColor(Vector4 c)`](VRageMath.UnmultiplyColor)||
|static [`Vector4 PremultiplyColor(Vector4 c)`](VRageMath.PremultiplyColor)||
|static [`Vector4 ToSRGB(Vector4 c)`](VRageMath.ToSRGB)||
|static [`Vector4 ToLinearRGB(Vector4 c)`](VRageMath.ToLinearRGB)||
|static [`Vector3 ToLinearRGB(Vector3 c)`](VRageMath.ToLinearRGB)||
|static [`Vector3 ToSRGB(Vector3 c)`](VRageMath.ToSRGB)||
|static [`Vector3 ToHsv(Vector3 rgb)`](VRageMath.ToHsv)||
|static [`Vector3 ToGray(Vector3 c)`](VRageMath.ToGray)||
|static [`Vector4 ToGray(Vector4 c)`](VRageMath.ToGray)||
|static [`float ToLinearRGBComponent(float c)`](VRageMath.ToLinearRGBComponent)||
|static [`float ToSRGBComponent(float c)`](VRageMath.ToSRGBComponent)||
|static [`Color Shade(Color c, float r)`](VRageMath.Shade)||
|static [`Color Tint(Color c, float r)`](VRageMath.Tint)||
|static [`Color Alpha(Color c, float a)`](VRageMath.Alpha)||
