# Array.ofSeq<'T> Function (F#)

Builds a new array from the given enumerable object.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
Array.ofSeq : seq<'T> -> 'T []

// Usage:
Array.ofSeq source
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*source*
Type: [seq](http://msdn.microsoft.com/en-us/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'T&gt;**


The input sequence.



**The array of elements from the sequence.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **OfSeq** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**Thhhe following code shows how to use Array.ofSeq.**
**[!CODE [FsArrays#60](../CodeSnippet/VS_Snippets_Fsharp/fsarrays/FSharp/fs/program.fs#60)]**
**FSI Output**
**val array1 : int [] = [|1; 2; 3; 4; 5; 6; 7; 8; 9; 10|]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

