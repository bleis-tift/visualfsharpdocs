# Parallel.init<'T> Function (F#)

Create an array given the dimension and a generator function to compute the elements.

**Namespace/Module Path:** Microsoft.FSharp.Collections.ArrayModule.Parallel

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
init : int -> (int -> 'T) -> 'T []

// Usage:
init count initializer
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*count*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)


The size of the array.


*initializer*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)**-&gt; 'T**


The function that generates the elements.



**The created array.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
Performs the operation in parallel using System.Threading.Tasks.Parallel.For. The order in which the given function is applied to indices is not specified.

This function is named **Initialize** in compiled assemblies. If you are accessing the function from a .NET language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0


## See Also
[Array.Parallel Module &#40;F&#35;&#41;](Array.Parallel+Module+28%F%2329%.md)

[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+28%F%2329%.md)

