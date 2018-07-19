The purpose of the minifier is to rename and compact your code in a way that allows you to fit _more_ code into the limited space allowed by the game. Rest assured that this is perfectly fine as the reason for the script limit is because of network transfer, not code performance or anything like that. _What_ you write is more important than _how much_ you write.

The minifier is split into two separate functions. The first and simplest is a way to remove types you are not using in your code. Simply enable the "Type Trimming" checkbox in the new MDK script wizard or in the script options dialog.

The second function is the fullblown minifier that removes all formatting, removes unnecessary whitespace and renames all symbols it can to the smallest symbol name it can use.

### Unminified Section
Some times there's code you don't want to be minified, for whatever reason. The unminified section system also works by code regions. Simply add the code or comments you wish to preserve within such a region to have the minifier skip over it. Be aware though, that it won't necessarily be completely untouched. Some minor adjustments might be made, but naming will be untouched, and formatting will _most probably_ be.
```cs
#region mdk preserve
// Stuff I don't want the minifier to touch
#endregion
```