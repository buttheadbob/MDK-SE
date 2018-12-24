← [Index](Api-Index) ← [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni)

[bool](System.Boolean) TryParse([string](System.String) content)

## Summary

Attempts to parse the given content as a configuration file.

## Returns

`true`if the parse succeeds,`false`otherwise

[bool](System.Boolean) TryParse([string](System.String) content, ref [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) result)

## Summary

Attempts to parse the given content as a configuration file.

## Returns

`true`if the parse succeeds,`false`otherwise

[bool](System.Boolean) TryParse([string](System.String) content, [string](System.String) section, ref [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) result)

## Summary

Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.

## Returns

`true`if the parse succeeds,`false`otherwise

[bool](System.Boolean) TryParse([string](System.String) content, [string](System.String) section)

## Summary

Attempts to parse the given content as a configuration file. OBSERVE: Use only for read-only operations. If you parse a single section and run [ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIni.ToString) , you will only get the parsed section, the rest will be discarded.

## Returns

`true`if the parse succeeds,`false`otherwise

