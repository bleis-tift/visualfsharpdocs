# Operators.( >> )<'T1,'T2,'T3> Function (F#)

Composes two functions, the function on the left being applied first

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
( >> ) : ('T1 -> 'T2) -> ('T2 -> 'T3) -> 'T1 -> 'T3

// Usage:
func1 >> func2
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*func1*
Type: **'T1 -&gt; 'T2**


The first function to apply.


*func2*
Type: **'T2 -&gt; 'T3**


The second function to apply.



**The composition of the input functions.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
**The following example demonstrates the use of the composition operator (&gt;&gt;).**
**[!CODE [FsOperators#7](../CodeSnippet/VS_Snippets_Fsharp/fsoperators/FSharp/fs/program.fs#7)]**
**abc.append1.append2**
**abc.append1.append2.append3**
**myfile.txt**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators+Module+28%F%2329%.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core+Namespace+28%F%2329%.md)

