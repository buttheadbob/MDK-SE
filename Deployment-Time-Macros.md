You can put deployment time information into your script automatically using certain macros. In order to both try to save a little time and to make sure these macros don't mess up any code, they only work inside special code regions.

```cs
#region mdk macros
// This script was deployed at $MDK_DATETIME$
const string Deployment = "$MDK_DATE$, $MDK_TIME$"
#endregion
```
