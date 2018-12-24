← [Index](Api-Index)

# MyIni Class

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

### Properties

|Member|Description|
|---|---|
|[EndContent](VRage.Game.ModAPI.Ingame.Utilities.MyIni.EndContent)|You can terminate a configuration stream by entering "---" on a separate line. This property will contain all the content after this line.|
|[EndComment](VRage.Game.ModAPI.Ingame.Utilities.MyIni.EndComment)|Get or set a comment to be placed after the last section or item. Is`null`if the section does not exist or has no comment.|

### Methods

|Member|Description|
|---|---|
|[HasSection(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.HasSection)|Determines if the given configuration contains what looks like the given section. It does not verify that the content is actually in a valid format, just if there's a line starting with [section].|
|[ContainsSection(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ContainsSection)|Determines whether a section of a given name exists in the currently parsed configuration.|
|[ContainsKey(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ContainsKey)|Determines whether a configuration key (section/key) exists in the currently parsed configuration.|
|[ContainsKey(MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ContainsKey)|Determines whether a configuration key (section/key) exists in the currently parsed configuration.|
|[GetKeys(string, List)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.GetKeys)||
|[GetKeys(List)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.GetKeys)||
|[GetSections(List)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.GetSections)||
|[SetEndComment(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.SetEndComment)|Sets a comment to be placed after the last section or item. Set the comment to`null`to remove it.|
|[GetSectionComment(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.GetSectionComment)|Get any comment that might be associated with the given section. Returns`null`if the section does not exist or has no comment.|
|[SetSectionComment(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.SetSectionComment)|Sets a comment on a given section. The section must already exist. Set the comment to`null`to remove it.|
|[GetComment(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.GetComment)|Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.|
|[GetComment(MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.GetComment)|Gets any comment that might be associated with the given key. Returns`null`if the key does not exist or has no comment.|
|[SetComment(string, string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.SetComment)|Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.|
|[SetComment(MyIniKey, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.SetComment)|Sets a comment on a given item. The item must already exist. Set the comment to`null`to remove it.|
|[Get(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Get)|Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.|
|[Get(MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Get)|Gets the [MyIniValue](VRage.Game.ModAPI.Ingame.Utilities.MyIniValue) of the given configuration key.|
|[Delete(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Delete)|Deletes the given configuration key.|
|[Delete(MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Delete)|Deletes the given configuration key.|
|[Set(string, string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, bool)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, bool)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, byte)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, byte)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, sbyte)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, sbyte)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, ushort)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, ushort)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, short)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, short)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, uint)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, uint)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, int)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, int)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, ulong)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, ulong)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, long)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, long)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, float)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, float)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, double)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, double)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(string, string, decimal)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Set(MyIniKey, decimal)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Set)|Sets the value of the given configuration key.|
|[Clear()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Clear)|Empties this configuration|
|[TryParse(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.TryParse)|Attempts to parse the given content as a configuration file.|
|[TryParse(string, ref MyIniParseResult)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.TryParse)|Attempts to parse the given content as a configuration file.|
|[TryParse(string, string, ref MyIniParseResult)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.TryParse)|Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.|
|[TryParse(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIni.TryParse)|Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.|
|[Invalidate()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.Invalidate)|Forces regeneration of the ini content. Only really useful if you want to reformat the configuration file.|
|[ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString)|Generates a configuration file from the currently parsed configuration|

