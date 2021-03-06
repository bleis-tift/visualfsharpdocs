# FSharpType.IsUnion Method (F#)

Returns **true** if the specified type is a representation of an F# union type or the runtime type of a value of that type.

**Namespace/Module Path:** Microsoft.FSharp.Reflection

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
static member IsUnion : Type * ?BindingFlags -> bool
static member IsUnion : Type * ?bool -> bool

// Usage:
FSharpType.IsUnion (typ)
FSharpType.IsUnion (typ, bindingFlags = bindingFlags)
open FSharpReflectionExtensions
FSharpType.IsUnion (type, allowAccesstoPrivateRepresentation = false)
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*typ*
Type: **T:System.Type**


The type to check.


*bindingFlags*
Type: **T:System.Reflection.BindingFlags**[option](http://msdn.microsoft.com/en-us/library/b08add48-34bf-4410-80a1-ef6a8daddc58)


Optional binding flags.


*allowAccessToPrivateRepresentation*
Type: [bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


Optional flag that denotes accessibility of the private representation.



**Returns true if the type check succeeds.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Reflection.FSharpType Class &#40;F&#35;&#41;](Reflection.FSharpType+Class+28%F%2329%.md)

[Microsoft.FSharp.Reflection Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Reflection+Namespace+28%F%2329%.md)

