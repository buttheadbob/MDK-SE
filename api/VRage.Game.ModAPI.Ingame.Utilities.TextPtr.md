← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### TextPtr Struct

```csharp
public struct TextPtr
```

A parser utility structure representing a pointer to a location within a string.

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

#### Fields

|Member|Description|
|---|---|
|[Content](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.Content)|The original content string|
|[Index](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.Index)|The index being pointed at by this structure|

#### Properties

|Member|Description|
|---|---|
|[Char { get; }](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.Char)|Returns the character currently being pointed at, or`\0`if out of bounds|
|[IsEmpty { get; }](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.IsEmpty)|Determines whether this pointer is an empty pointer, i.e. not pointing at anything at all.|

#### Constructors

|Member|Description|
|---|---|
|[TextPtr(string)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr..ctor)||
|[TextPtr(string, int)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr..ctor)||

#### Methods

|Member|Description|
|---|---|
|[IsOutOfBounds()](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.IsOutOfBounds)|Determines whether this pointer is currently out of bounds (before or after the string content)|
|[FindLineNo()](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.FindLineNo)|Determines what line number this pointer is currently at.|
|[Find(string)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.Find)|Finds the given text string|
|[Find(char)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.Find)|Finds the given character|
|[FindAny(Char[])](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.FindAny)|Finds one of the given characters|
|[FindInLine(char)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.FindInLine)|Finds the given character within the current line|
|[FindAnyInLine(Char[])](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.FindAnyInLine)|Finds one of the given characters within the current line|
|[FindEndOfLine(bool)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.FindEndOfLine)|Finds the end of the current line|
|[StartsWithCaseInsensitive(string)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.StartsWithCaseInsensitive)|Determines if the current pointer location starts with the given string - in a case insensitive manner.|
|[StartsWith(string)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.StartsWith)|Determines if the current pointer location starts with the given string - in a case sensitive manner.|
|[SkipWhitespace(bool)](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.SkipWhitespace)|Skips whitespace|
|[IsEndOfLine()](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.IsEndOfLine)|Determines whether the pointer is currently at the end of a line (right before a newline character set or end of the string)|
|[IsStartOfLine()](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.IsStartOfLine)|Determines whether the pointer is currently at the beginning of a line (right after a newline character set or start of the string)|
|[IsNewLine()](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.IsNewLine)|Determines whether the pointer is currently at a newline (end of the string is not a newline)|
|[TrimStart()](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.TrimStart)|Advances the pointer location until all whitespace is skipped - does not skip newlines|
|[TrimEnd()](VRage.Game.ModAPI.Ingame.Utilities.TextPtr.TrimEnd)|Reverses the pointer location until all whitespace is skipped - does not skip newlines|

