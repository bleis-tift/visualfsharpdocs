# AsyncBuilder.TryWith<'T> Method (F#)

Implements **try...with** in asynchronous computations.

**Namespace/Module Path:** Microsoft.FSharp.Control

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
member this.TryWith : Async<'T> * (exn -> Async<'T>) -> Async<'T>

// Usage:
asyncBuilder.TryWith (computation, catchHandler)
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*computation*
Type: [Async](http://msdn.microsoft.com/en-us/library/e0b28ea2-dea5-4021-b2b9-d7d4761babde)**&lt;'T&gt;**


The input computation.


*catchHandler*
Type: [exn](http://msdn.microsoft.com/en-us/library/e1569b69-3b30-440b-8c6f-966d1c6a06ab)**-&gt;**[Async](http://msdn.microsoft.com/en-us/library/e0b28ea2-dea5-4021-b2b9-d7d4761babde)**&lt;'T&gt;**


The function to run when *computation* throws an exception.



**An asynchronous computation that executes computation and calls catchHandler if an exception is thrown.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function creates an asynchronous computation that runs *computation* and returns its result. If an exception happens then **catchHandler(exn)** is called and the resulting computation executed instead.

A cancellation check is performed when the computation is executed. The existence of this method permits the use of **try...with** in the **async { ... }** computation expression syntax.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Control.AsyncBuilder Class &#40;F&#35;&#41;](Control.AsyncBuilder+Class+28%F%2329%.md)

[Microsoft.FSharp.Control Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Control+Namespace+28%F%2329%.md)

