# Array.choose<'T,'U> Function (F#)

Applies the given function to each element of the array. Returns the array comprised of the results **x** for each element where the function returns **Some(x)**.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
Array.choose : ('T -> 'U option) -> 'T [] -> 'U []

// Usage:
Array.choose chooser array
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*chooser*
Type: **'T -&gt; 'U**[option](http://msdn.microsoft.com/en-us/library/b08add48-34bf-4410-80a1-ef6a8daddc58)


The function to generate options from the elements.


*array*
Type: **'T**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The input array.



**The array of results.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **Choose** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code demonstrates the use of Array.choose to perform an operation only on the even numbers in an array.**
**[!CODE [FsArrays#14](../CodeSnippet/VS_Snippets_Fsharp/fsarrays/FSharp/fs/program.fs#14)]**
**[|3.0; 15.0; 35.0; 63.0; 99.0|]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

