# List.concat<'T> Function (F#)

Returns a new list that contains the elements of each list in order.

**Namespace/Module Path:** Microsoft.FSharp.Collections.List

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
List.concat : seq<'T list> -> 'T list

// Usage:
List.concat lists
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*lists*
Type: [seq](http://msdn.microsoft.com/en-us/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'T list&gt;**


The input sequence of lists.



**The resulting concatenated list.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **Concat** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code example illustrates that [List.append](http://msdn.microsoft.com/en-us/library/2954da80-3f4a-4a4b-9371-794645c03426) is used to join two lists together; and List.concat is used to join any number of lists.**
**[!CODE [FsLists#26](../CodeSnippet/VS_Snippets_Fsharp/fslists/FSharp/fs/program.fs#26)]**
**Output**
**1 2 3 4 5 6 7 8 9 10**
**1 2 3 4 5 6 7 8 9**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.List Module &#40;F&#35;&#41;](Collections.List+Module+28%F%2329%.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+28%F%2329%.md)

