# Async.Ignore<'T> Method (F#)

Creates an asynchronous computation that runs the given computation and ignores its result.

**Namespace/Module Path:** Microsoft.FSharp.Control

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
static member Ignore : Async<'T> -> Async<unit>

// Usage:
Async.Ignore (computation)
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*computation*
Type: [Async](http://msdn.microsoft.com/en-us/library/e0b28ea2-dea5-4021-b2b9-d7d4761babde)**&lt;'T&gt;**


The input computation.



**A computation that is equivalent to the input computation, but disregards the result.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
**The following code example illustrates the use of Async.Ignore.**
**[!CODE [FsAsyncAPIs#34](../CodeSnippet/VS_Snippets_Fsharp/fsasyncapis/FSharp/fs/program.fs#34)]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Control.Async Class &#40;F&#35;&#41;](Control.Async+Class+28%F%2329%.md)

[Microsoft.FSharp.Control Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Control+Namespace+28%F%2329%.md)

