# Core.EntryPointAttribute Class (F#)

Adding this attribute to a function indicates it is the entry point for an application. If this absent is not specified for an EXE then the initialization implicit in the module bindings in the last file in the compilation sequence are used as the entry point.

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
[<AttributeUsage(AttributeTargets.Method, AllowMultiple = false)>]
[<Sealed>]
type EntryPointAttribute =
class
new EntryPointAttribute : unit -> EntryPointAttribute
end
```

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
You can also use the short form of the name, **EntryPoint**.


## Constructors


|Member|Description|
|------|-----------|
|[new](http://msdn.microsoft.com/en-us/library/48ccf8e2-f6af-431d-8a90-bd2870df5c43)|Creates an instance of the attribute.|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+28%F%2329%.md)

[Entry Point &#40;F&#35;&#41;](Entry+Point+28%F%2329%.md)

