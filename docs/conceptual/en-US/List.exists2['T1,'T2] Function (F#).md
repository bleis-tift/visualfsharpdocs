# List.exists2<'T1,'T2> Function (F#)

Tests if any pair of corresponding elements of the lists satisfies the given predicate.

**Namespace/Module Path:** Microsoft.FSharp.Collections.List

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
List.exists2 : ('T1 -> 'T2 -> bool) -> 'T1 list -> 'T2 list -> bool

// Usage:
List.exists2 predicate list1 list2
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*predicate*
Type: **'T1 -&gt; 'T2 -&gt;**[bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


The function to test the input elements.


*list1*
Type: **'T1**[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)


The first input list.


*list2*
Type: **'T2**[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)


The second input list.



**true if any pair of elements satisfy the predicate. Otherwise, returns false.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
The predicate is applied to matching elements in the two collections up to the lesser of the two lengths of the collections. If any application returns true then the overall result is true and no further elements are tested.

This function is named **Exists2** in compiled assemblies. If you are accessing the function from a .NET language other than F#, or through reflection, use this name.

**The following code example illustrates the use of List.exists2.**
**[!CODE [FsLists#2](../CodeSnippet/VS_Snippets_Fsharp/fslists/FSharp/fs/program.fs#2)]**
**Output**
**Lists [1; 2; 3; 4; 5] and [5; 4; 3; 2; 1] have at least one equal element at the same position.**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.List Module &#40;F&#35;&#41;](Collections.List+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

