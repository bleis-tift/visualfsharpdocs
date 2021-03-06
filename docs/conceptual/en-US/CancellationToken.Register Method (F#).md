# CancellationToken.Register Method (F#)

Registers an action to perform with the CancellationToken.

**Namespace/Module Path**: System.Threading

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
member this.Register : Action<obj> * obj -> CancellationTokenRegistration

// Usage:
cancellationToken.Register (action, state)
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*action*
Type: **T:System.Action&#96;1****&lt;**[obj](http://msdn.microsoft.com/en-us/library/dcf2430f-702b-40e5-a0a1-97518bf137f7)**&gt;**


The action to associate with the token.


*state*
Type: [obj](http://msdn.microsoft.com/en-us/library/dcf2430f-702b-40e5-a0a1-97518bf137f7)


The state associated with the action.



**The created registration object.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This API is provided for use only with the F# Core Library Versions that targets .NET Framework 2.0. If you are using .NET Framework 4, use the .NET Framework 4 API with the same name, **M:System.Threading.CancellationToken.Register(System.Action{System.Object},System.Object)**.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0




## See Also
[Threading.CancellationToken Structure &#40;F&#35;&#41;](Threading.CancellationToken+Structure+28%F%2329%.md)

[System.Threading Namespace &#40;F&#35;&#41;](System.Threading+Namespace+28%F%2329%.md)

