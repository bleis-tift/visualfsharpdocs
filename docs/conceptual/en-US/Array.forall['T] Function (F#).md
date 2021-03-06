# Array.forall<'T> Function (F#)

Tests if all elements of the array satisfy the given predicate.

**Namespace/Module Path:** Microsoft.FSharp.Collections.Array

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
Array.forall : ('T -> bool) -> 'T [] -> bool

// Usage:
Array.forall predicate array
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*predicate*
Type: **'T -&gt;**[bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


The function to test the input elements.


*array*
Type: **'T**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The input array.



**true if all of the array elements satisfy the predicate. Otherwise, returns false.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
The predicate is applied to the elements of the input collection. If any application returns false then the overall result is false and no further elements are tested.

This function is named **ForAll** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following example shows the use of Array.forall to test the elements of an array.**
**[!CODE [FsArrays#241](../CodeSnippet/VS_Snippets_Fsharp/fsarrays/FSharp/fs/program.fs#241)]**
**false**
**true**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

