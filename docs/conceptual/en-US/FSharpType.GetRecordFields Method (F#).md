# FSharpType.GetRecordFields Method (F#)

Reads all the fields from a record value, in declaration order.

**Namespace/Module Path:** Microsoft.FSharp.Reflection

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
static member GetRecordFields : Type * ?BindingFlags -> PropertyInfo []
static member GetRecordFields : Type * ?bool -> PropertyInfo []

// Usage:
FSharpType.GetRecordFields (recordType)
FSharpType.GetRecordFields (recordType, bindingFlags = bindingFlags)

open FSharpReflectionExtensions
FSharpType.GetExceptionFields (recordType, allowAccessToPrivateRepresentation = false)
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*recordType*
Type: **T:System.Type**


The input record type.


*bindingFlags*
Type: **T:System.Reflection.BindingFlags**


Optional binding flags.


*allowAccessToPrivateRepresentation*
Type: [bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


Optional flag that denotes accessibility of the private representation.



**An array of descriptions of the properties (T:System.Reflection.PropertyInfo objects) of the record type.****exceptions tag is not supported!!!!**

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Reflection.FSharpType Class &#40;F&#35;&#41;](Reflection.FSharpType+Class+28%F%2329%.md)

[Microsoft.FSharp.Reflection Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Reflection+Namespace+28%F%2329%.md)

