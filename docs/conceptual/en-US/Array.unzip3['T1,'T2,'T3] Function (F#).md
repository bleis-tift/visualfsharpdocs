# Array.unzip3<'T1,'T2,'T3> Function (F#)

Splits an array of triples into three arrays.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
Array.unzip3 : ('T1 * 'T2 * 'T3) [] -> 'T1 [] * 'T2 [] * 'T3 []

// Usage:
Array.unzip3 array
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*array*
Type: **('T1 &#42; 'T2 &#42; 'T3)**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The input array.



**The tuple of three arrays.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **Unzip3** in compiled assemblies. If accessing the function from a language other than F#, or through reflection, use this name.

**The following code shows how to use Array.unzip3.**
**[!CODE [FsArrays#71](../CodeSnippet/VS_Snippets_Fsharp/fsarrays/FSharp/fs/program.fs#71)]**
**Output**
**[|1; 3|]**
**[|2; 4|]**
**[|3; 5|]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

