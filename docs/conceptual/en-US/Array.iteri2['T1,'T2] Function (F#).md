# Array.iteri2<'T1,'T2> Function (F#)

Applies the given function to a pair of elements drawn from matching indices in two arrays, also passing the index of the elements. The two arrays must have the same lengths, otherwise **T:System.ArgumentException** is raised.

**Namespace/Module Path**: Microsoft.FSharp.Collections.Array

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
Array.iteri2 : (int -> 'T1 -> 'T2 -> unit) -> 'T1 [] -> 'T2 [] -> unit

// Usage:
Array.iteri2 action array1 array2
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*action*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)**-&gt; 'T1 -&gt; 'T2 -&gt;**[unit](http://msdn.microsoft.com/en-us/library/00b837c2-6c8a-483a-87d3-0479c64037a7)


The function to apply to each index and pair of elements.


*array1*
Type: **'T1**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The first input array.


*array2*
Type: **'T2**[[]](http://msdn.microsoft.com/en-us/library/def20292-9aae-4596-9275-b94e594f8493)


The second input array.



**exceptions tag is not supported!!!!**

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **IterateIndexed2** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code examples shows the differences between [Array.iter](http://msdn.microsoft.com/en-us/library/94eba0f1-ecd7-459f-b89f-ed2a2923e516), [Array.iter2](http://msdn.microsoft.com/en-us/library/018aa9b9-f186-4142-be8a-a62462794fdc), [Array.iteri](http://msdn.microsoft.com/en-us/library/8bbe2ed4-ada7-4906-ac3e-cb09f9db6486), and Array.iteri2.**
**[!CODE [FsArrays#49](../CodeSnippet/VS_Snippets_Fsharp/fsarrays/FSharp/fs/program.fs#49)]**
**Output**
**Array.iter: element is 1**
**Array.iter: element is 2**
**Array.iter: element is 3**
**Array.iteri: element 0 is 1**
**Array.iteri: element 1 is 2**
**Array.iteri: element 2 is 3**
**Array.iter2: elements are 1 4**
**Array.iter2: elements are 2 5**
**Array.iter2: elements are 3 6**
**Array.iteri2: element 0 of array1 is 1 element 0 of array2 is 4**
**Array.iteri2: element 1 of array1 is 2 element 1 of array2 is 5**
**Array.iteri2: element 2 of array1 is 3 element 2 of array2 is 6**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Array Module &#40;F&#35;&#41;](Collections.Array+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

