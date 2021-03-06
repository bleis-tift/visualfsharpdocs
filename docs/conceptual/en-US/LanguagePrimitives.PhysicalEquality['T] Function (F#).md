# LanguagePrimitives.PhysicalEquality<'T> Function (F#)

Implements reference, or *physical* equality.

**Namespace/Module Path:** Microsoft.FSharp.Core.LanguagePrimitives

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
PhysicalEquality : 'T -> 'T -> bool (requires reference type)

// Usage:
PhysicalEquality e1 e2
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*e1*
Type: **'T**


The first value.


*e2*
Type: **'T**


The second value.



**true if boxed versions of the inputs are reference-equal, or if both are primitive numeric types and the implementation of M:System.Object.Equals(System.Object) for the type of the first argument returns true on the boxed version of the inputs.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library VersionsF# Core Library Versions**

Supported in: 2.0, 4.0, PortablePortable2.0, 4.0, Portable




## See Also
[Core.LanguagePrimitives Module &#40;F&#35;&#41;](Core.LanguagePrimitives+Module+28%F%2329%.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+28%F%2329%.md)

