# Control.Async<'T> Type (F#)

A compositional asynchronous computation, which, when run, will eventually produce a value of type 'T, or else raises an exception. The functions for working with these objects are in the [Async](http://msdn.microsoft.com/en-us/library/03eb4d12-a01a-4565-a077-5e83f17cf6f7) class.

**Namespace/Module Path:** Microsoft.FSharp.Control

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
[<Sealed>]
[<NoEquality>]
[<NoComparison>]
type Async<'T> =
class
end
```

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
Asynchronous computations are normally specified using an F# computation expression. When run, asynchronous computations have two modes: as a work item (executing synchronous code), or as a wait item (waiting for an event or I/O completion). When run, asynchronous computations can be governed by **T:System.Threading.CancellationToken**. This can usually be specified when the asynchronous computation is started. The associated **T:System.Threading.CancellationTokenSource** may be used to cancel the asynchronous computation. Asynchronous computations built using computation expressions can check the cancellation condition regularly. Synchronous computations within an asynchronous computation do not automatically check this condition. For more information, see [Asynchronous Workflows &#40;F&#35;&#41;](Asynchronous+Workflows+28%F%2329%.md).

This type is named **FSharpAsync** in compiled assemblies. If you are accessing the type from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Control Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Control+Namespace+28%F%2329%.md)

[Control.Async Class &#40;F&#35;&#41;](Control.Async+Class+28%F%2329%.md)

[Asynchronous Workflows &#40;F&#35;&#41;](Asynchronous+Workflows+28%F%2329%.md)

