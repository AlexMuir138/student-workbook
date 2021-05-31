Journal 16

What are the three states of a Promise?

Pending, resolved, rejected

How do promises seek to resolve the issues of "callback hell"?
Chaining is probably one of the better advantages. You can chain functions to fire depenging on the result of the promise and catch the error right where it happens.

What is the difference between .then() and .catch()?

The then() function has to fail in order for the catch() to fire. Catch is essentially a failsafe.

https://alexmuir138.github.io/summer21-gregslist-v1/