# Nullable.enum<^U> Function (F#)

Converts the argument to a particular enum type.

**Namespace/Module Path**: Microsoft.FSharp.Linq.Nullable

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
enum : Nullable<int32> -> Nullable<^U> when ^U : enum<int32> and ^U : (new : unit ->  ^U) and ^U : struct and ^U :> ValueType

// Usage:
Nullable.enum value
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*value*
Type: **T:System.Nullable&#96;1**&lt;[int32](http://msdn.microsoft.com/en-us/library/6ab0ea34-03db-4874-a265-bef9c64f8eff)&gt;


The input value.




## Return Value
The converted enum type.


## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **ToEnum** in the .NET assembly. If accessing the member from a .NET language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Linq.Nullable Module &#40;F&#35;&#41;](Linq.Nullable+Module+28%F%2329%.md)

[Microsoft.FSharp.Linq Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Linq+Namespace+28%F%2329%.md)

[Operators.enum&#60;^U&#62; Function &#40;F&#35;&#41;](Operators.enum%3C%5EU%3E+Function+28%F%2329%.md)

[Enumerations (F#)](http://msdn.microsoft.com/en-us/library/74192be5-bb8d-499d-b540-283cecd999cd)

