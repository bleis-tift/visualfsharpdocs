# List.foldBack2<'T1,'T2,'State> Function (F#)

Applies a function to corresponding elements of two collections, threading an accumulator argument through the computation. The collections must have identical sizes. If the input function is **f** and the elements are **i0...iN** and **j0...jN**, then this function computes **f i0 j0 (...(f iN jN s))**.

**Namespace/Module Path:** Microsoft.FSharp.Collections.List

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
List.foldBack2 : ('T1 -> 'T2 -> 'State -> 'State) -> 'T1 list -> 'T2 list -> 'State -> 'State

// Usage:
List.foldBack2 folder list1 list2 state
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*folder*
Type: **'T1 -&gt; 'T2 -&gt; 'State -&gt; 'State**


The function to update the state given the input elements.


*list1*
Type: **'T1**[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)


The first input list.


*list2*
Type: **'T2**[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)


The second input list.


*state*
Type: **'State**


The initial state.



**The final state value.****exceptions tag is not supported!!!!**

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **FoldBack2** in compiled assemblies. If you are accessing the function from a .NET language other than F#, or through reflection, use this name.

The following code examples illustrate the difference between [List.fold2](http://msdn.microsoft.com/en-us/library/6cfcd043-a65d-4423-805a-2ab234cb5343) and **List.foldBack2**.

**[!CODE [FsLists#31](../CodeSnippet/VS_Snippets_Fsharp/fslists/FSharp/fs/program.fs#31)]**
**Output**
**1210.020833****[!CODE [FsLists#32](../CodeSnippet/VS_Snippets_Fsharp/fslists/FSharp/fs/program.fs#32)]**
**Output**
**1205.833333**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.List Module &#40;F&#35;&#41;](Collections.List+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

