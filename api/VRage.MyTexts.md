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
|[static MyStringId GAMEPAD_VARIANT_ID](VRage.MyTexts.GAMEPAD_VARIANT_ID)||

#### Properties

|Member|Description|
|---|---|
|[static MyStringId GlobalVariantSelector { get; }](VRage.MyTexts.GlobalVariantSelector)|Global selector for translation variants.|
|[static DictionaryReader&lt;MyLanguagesEnum, MyLanguageDescription&gt; Languages { get; }](VRage.MyTexts.Languages)||

#### Methods

|Member|Description|
|---|---|
|[static StringBuilder AppendFormat(this StringBuilder, MyStringId, object)](VRage.MyTexts.AppendFormat)||
|[static StringBuilder AppendFormat(this StringBuilder, MyStringId, Object&#91&#93;)](VRage.MyTexts.AppendFormat)||
|[static StringBuilder AppendFormat(this StringBuilder, MyStringId, MyStringId)](VRage.MyTexts.AppendFormat)||
|[static void Clear()](VRage.MyTexts.Clear)||
|[static bool Exists(MyStringId)](VRage.MyTexts.Exists)||
|[static StringBuilder Get(MyStringId)](VRage.MyTexts.Get)||
|[static MyLanguagesEnum GetBestSuitableLanguage(string)](VRage.MyTexts.GetBestSuitableLanguage)||
|[static string GetString(MyStringId)](VRage.MyTexts.GetString)||
|[static string GetString(string)](VRage.MyTexts.GetString)||
|[static string GetSystemLanguage()](VRage.MyTexts.GetSystemLanguage)||
|[static bool IsTagged(string, int, string)](VRage.MyTexts.IsTagged)||
|[static void LoadSupportedLanguages(string, HashSet&lt;MyLanguagesEnum&gt;)](VRage.MyTexts.LoadSupportedLanguages)||
|[static void LoadTexts(string, string = null, string = null)](VRage.MyTexts.LoadTexts)||
|[static bool MatchesReplaceFormat(string)](VRage.MyTexts.MatchesReplaceFormat)||
|[static void RegisterEvaluator(string, ITextEvaluator)](VRage.MyTexts.RegisterEvaluator)||
|[static void SetGlobalVariantSelector(MyStringId)](VRage.MyTexts.SetGlobalVariantSelector)|Set the global variant to be selected for each translation.|
|[static string SubstituteTexts(string, string = null)](VRage.MyTexts.SubstituteTexts)||
|[static StringBuilder SubstituteTexts(StringBuilder)](VRage.MyTexts.SubstituteTexts)||
|[static string TrySubstitute(string)](VRage.MyTexts.TrySubstitute)||

