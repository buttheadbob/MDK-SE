← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyTexts Class

```csharp
public abstract sealed class MyTexts
```

**Namespace:** [VRage](VRage)  
**Assembly:** VRage.dll

#### Fields

|Member|Description|
|---|---|
|\\%1static MyStringId GAMEPAD_VARIANT_ID](VRage.MyTexts.GAMEPAD_VARIANT_ID)||

#### Properties

|Member|Description|
|---|---|
|\\%1static MyStringId GlobalVariantSelector { get; }](VRage.MyTexts.GlobalVariantSelector)|Global selector for translation variants.|
|\\%1static DictionaryReader\\%1MyLanguagesEnum, MyLanguageDescription> Languages { get; }](VRage.MyTexts.Languages)||

#### Methods

|Member|Description|
|---|---|
|\\%1static StringBuilder AppendFormat(this StringBuilder, MyStringId, object)](VRage.MyTexts.AppendFormat)||
|\\%1static StringBuilder AppendFormat(this StringBuilder, MyStringId, Object\\%1])](VRage.MyTexts.AppendFormat)||
|\\%1static StringBuilder AppendFormat(this StringBuilder, MyStringId, MyStringId)](VRage.MyTexts.AppendFormat)||
|\\%1static void Clear()](VRage.MyTexts.Clear)||
|\\%1static bool Exists(MyStringId)](VRage.MyTexts.Exists)||
|\\%1static StringBuilder Get(MyStringId)](VRage.MyTexts.Get)||
|\\%1static MyLanguagesEnum GetBestSuitableLanguage(string)](VRage.MyTexts.GetBestSuitableLanguage)||
|\\%1static string GetString(MyStringId)](VRage.MyTexts.GetString)||
|\\%1static string GetString(string)](VRage.MyTexts.GetString)||
|\\%1static string GetSystemLanguage()](VRage.MyTexts.GetSystemLanguage)||
|\\%1static bool IsTagged(string, int, string)](VRage.MyTexts.IsTagged)||
|\\%1static void LoadSupportedLanguages(string, HashSet\\%1MyLanguagesEnum>)](VRage.MyTexts.LoadSupportedLanguages)||
|\\%1static void LoadTexts(string, \\%1string], \\%1string])](VRage.MyTexts.LoadTexts)||
|\\%1static bool MatchesReplaceFormat(string)](VRage.MyTexts.MatchesReplaceFormat)||
|\\%1static void RegisterEvaluator(string, ITextEvaluator)](VRage.MyTexts.RegisterEvaluator)||
|\\%1static void SetGlobalVariantSelector(MyStringId)](VRage.MyTexts.SetGlobalVariantSelector)|Set the global variant to be selected for each translation.|
|\\%1static string SubstituteTexts(string, \\%1string])](VRage.MyTexts.SubstituteTexts)||
|\\%1static StringBuilder SubstituteTexts(StringBuilder)](VRage.MyTexts.SubstituteTexts)||
|\\%1static string TrySubstitute(string)](VRage.MyTexts.TrySubstitute)||

