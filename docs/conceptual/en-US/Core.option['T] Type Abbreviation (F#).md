# Core.option<'T> Type Abbreviation (F#)

The type of optional values. When used from other .NET Framework languages the empty option is the **null** value. This type is a type abbreviation for [Option](http://msdn.microsoft.com/en-us/library/b08add48-34bf-4410-80a1-ef6a8daddc58).

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
type option<'T> = Option<'T>
```

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
Use the constructors **Some** and **None** to create values of this type. Use the values in the [Option module](http://msdn.microsoft.com/en-us/library/e615e4d3-bbbb-49ba-addc-6061ea2e2f4c) to manipulate values of this type, or pattern match against the values directly. **None** values will appear as the value **null** to other .NET Framework languages. Instance methods on this type will appear as static methods to other .NET Framework languages due to the use of **null** as a value representation.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+28%F%2329%.md)

[Core.Option&#60;'T&#62; Union &#40;F&#35;&#41;](Core.Option%3C%27T%3E+Union+28%F%2329%.md)

