What is Scope ?

Scope is where the variables used outside of functions are available for use.

What is Hoisting ?

Hoisting is a JS mechanism where variable and function declarations are moved to the top of their scope before code execution. 

In what cases might you use let vs const vs var?

The biggest difference that I find between these is actually between const and let/var. There isn't a huge difference in let/var besides how you can redefine them in blocks. Var will return errors if you try and redefine them in blocks, whereas you can write if declarations to redefine let declarations. With const declarations they cannot be updated or re-declared. So if you want something that is permanent and does not faulter from its original assignment, use const statements.

