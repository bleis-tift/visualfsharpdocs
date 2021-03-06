# FSharpValue.GetRecordFields Method (F#)

Reads all the fields from a record value.

**Namespace/Module Path:** Microsoft.FSharp.Reflection

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
static member GetRecordFields : obj * ?BindingFlags -> obj []
static member GetRecordFields : obj * ?bool -> obj []
// Usage:
FSharpValue.GetRecordFields (record)
FSharpValue.GetRecordFields (record, bindingFlags = bindingFlags)

open FSharpReflectionExtensions
FSharpValue.GetRecordFields (record, allowAccessToPrivateRepresentation = false)
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*record*
Type: [obj](http://msdn.microsoft.com/en-us/library/dcf2430f-702b-40e5-a0a1-97518bf137f7)


The record object.


*bindingFlags*
Type: **T:System.Reflection.BindingFlags**


Optional binding flags for the record.


*allowAccessToPrivateRepresentation*
Type: [bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


Optional flag that denotes accessibility of the private representation.



**exceptions tag is not supported!!!!**
**The array of fields from the record.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Reflection.FSharpValue Class &#40;F&#35;&#41;](Reflection.FSharpValue+Class+28%F%2329%.md)

[Microsoft.FSharp.Reflection Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Reflection+Namespace+28%F%2329%.md)

