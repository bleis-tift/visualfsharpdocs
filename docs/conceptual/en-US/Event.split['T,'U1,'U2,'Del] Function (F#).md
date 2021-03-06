# Event.split<'T,'U1,'U2,'Del> Function (F#)

Returns a new event that listens to the original event and triggers the first resulting event if the application of the function to the event arguments returned a **Choice1Of2**, and the second event if it returns a **Choice2Of2**.

**Namespace/Module Path:** Microsoft.FSharp.Control.Event

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
// Signature:
Event.split : ('T -> Choice<'U1,'U2>) -> IEvent<'Del,'T> -> IEvent<'U1> * IEvent<'U2> (requires delegate)

// Usage:
Event.split splitter sourceEvent
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*splitter*
Type: **'T -&gt;**[Choice](http://msdn.microsoft.com/en-us/library/2ab2513e-e307-4360-96cd-8b682a8d64f0)**&lt;'U1,'U2&gt;**


A function, typically an active pattern recognizer, that transforms event values into one of two types.


*sourceEvent*
Type: [IEvent](http://msdn.microsoft.com/en-us/library/8dbca0df-f8a1-40bd-8d50-aa26f6a8b862)**&lt;'Del,'T&gt;**


The input event.



**A tuple of events. The first fires whenever splitter evaluates to Choice1of1 and the second fires whenever splitter evaluates to Choice2of2.**
## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
This function is named **Split** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code shows how to use the Event.split function to implement the ability to move a control on a form. The splitter function is the active pattern recognizer (|Down|Up|), which represents the state of the mouse buttons. If a user presses the mouse button while moving the mouse when it is over the button, the button moves. There is also code that sometimes changes the color of the button while it is moving, depending on which mouse button is used. This test uses a different color for each mouse button. The other event path, which is used when the mouse button is not down, restores the original color of the button after the button is released.**
**[!CODE [FsEvents#9](../CodeSnippet/VS_Snippets_Fsharp/fsevents/FSharp/fs/program.fs#9)]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Control.Event Module &#40;F&#35;&#41;](Control.Event+Module+28%F%2329%.md)

[Microsoft.FSharp.Control Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Control+Namespace+28%F%2329%.md)

