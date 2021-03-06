# Flexible Types (F#)

A *flexible type annotation* indicates that a parameter, variable, or value has a type that is compatible with a specifed type, where compatibility is determined by position in an object-oriented hierarchy of classes or interfaces. Flexible types are useful specifically when the automatic conversion to types higher in the type hierarchy does not occur but you still want to enable your functionality to work with any type in the hierarchy or any type that implements an interface.


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
#type
```

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
In the previous syntax, *type* represents a base type or an interface.

A flexible type is equivalent to a generic type that has a constraint that limits the allowed types to types that are compatible with the base or interface type. That is, the following two lines of code are equivalent.

**#SomeType**

**'a when 'a :&gt; SomeType**

Flexible types are useful in several types of situations. For example, when you have a higher order function (a function that takes a function as an argument), it is often useful to have the function return a flexible type. In the following example, the use of a flexible type with a sequence argument in **iterate2** enables the higher order function to work with functions that generate sequences, arrays, lists, and any other enumerable type.

Consider the following two functions, one of which returns a sequence, the other of which returns a flexible type.

[!CODE [FsLangRef2#4101](../CodeSnippet/VS_Snippets_Fsharp/fslangref2/FSharp/fs/flexibletypes.fs#4101)]
    As another example, consider the [Seq.concat](http://msdn.microsoft.com/en-us/library/2eeb69a9-fc2f-4b7d-8dee-101fa2b00712) library function:


```
val concat: sequences:seq<#seq<'T>> -> seq<'T>
```
You can pass any of the following enumerable sequences to this function:


- A list of lists
<br />

- A list of arrays
<br />

- An array of lists
<br />

- An array of sequences
<br />

- Any other combination of enumerable sequences
<br />

The following code uses **Seq.concat** to demonstrate the scenarios that you can support by using flexible types.

[!CODE [FsLangRef2#4102](../CodeSnippet/VS_Snippets_Fsharp/fslangref2/FSharp/fs/flexibletypes.fs#4102)]
    The output is as follows.


```
seq [1; 2; 3; 4; ...]
seq [1; 2; 3; 4; ...]
seq [1; 2; 3; 4; ...]
seq [1; 2; 3; 4; ...]
seq [1; 2; 3; 4; ...]
```
In F#, as in other object-oriented languages, there are contexts in which derived types or types that implement interfaces are automatically converted to a base type or interface type. These automatic conversions occur in direct arguments, but not when the type is in a subordinate position, as part of a more complex type such as a return type of a function type, or as a type argument. Thus, the flexible type notation is primarily useful when the type you are applying it to is part of a more complex type.


## See Also
[F&#35; Language Reference](F%23+Language+Reference.md)

[Generics &#40;F&#35;&#41;](Generics+28%F%2329%.md)

