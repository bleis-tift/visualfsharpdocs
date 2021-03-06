# Unchecked.defaultof<'T> Type Function (F#)

Generate a default value for any type. This is **null** for reference types. For structures, this is structure value where all fields have the default value. This function is unsafe in the sense that some F# values do not have proper **null** values.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators.Unchecked

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
defaultof<'T> :  'T

// Usage:
defaultof
```

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **DefaultOf** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Operators.Unchecked Module &#40;F&#35;&#41;](Operators.Unchecked+Module+28%F%2329%.md)

[Core.Operators Module &#40;F&#35;&#41;](Core.Operators+Module+28%F%2329%.md)

