# Conditional Expressions: if... then...else (F#)

The **if...then...else** expression runs different branches of code and also evaluates to a different value depending on the Boolean expression given.


## [!INCLUDE[System_CAPS_syntax](//System/Token/System_CAPS_syntax_md.md)]

```
if Boolean-expression then expression1 [ else expression2 ]
```

## [!INCLUDE[System_CAPS_remarks](//System/Token/System_CAPS_remarks_md.md)]
In the previous syntax, *expression1* runs when the Boolean expression evaluates to **true**; otherwise, *expression2* runs.

Unlike in other languages, the **if...then...else** construct is an expression, not a statement. That means that it produces a value, which is the value of the last expression in the branch that executes. The types of the values produced in each branch must match. If there is no explicit **else** branch, its type is **unit**. Therefore, if the type of the **then** branch is any type other than **unit**, there must be an **else** branch with the same return type. When chaining **if...then...else** expressions together, you can use the keyword **elif** instead of **else****if**; they are equivalent.

**The following example illustrates how to use the if...then...else expression.**
**[!CODE [FsLangRef2#4501](../CodeSnippet/VS_Snippets_Fsharp/fslangref2/FSharp/fs/conditionalexpressions.fs#4501)]**
**John**
**910 is less than 20**
**You are only 9 years old and already learning F#? Wow!**
## See Also
[F&#35; Language Reference](F%23+Language+Reference.md)

