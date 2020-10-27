
# Read 9

## Concepts of Functional Programming in JavaScript

how do we know if a function is pure or not? Here is a very strict definition of purity:

-It returns the same result if given the same arguments (it is also referred as deterministic).

-It does not cause any observable side effects.

-If our function reads external files, it’s not a pure function — the file’s contents can change.

-Any function that relies on a random number generator cannot be pure.

-Mutability is discouraged in functional programming.

-Pure functions are stable, consistent, and predictable. Given the same parameters, pure functions will always return the same result. We don’t need to think of situations when the same parameter has different results — because it will never happen.

-When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

-In JavaScript we commonly use the for loop.

-The idea of functions as first-class entities is that functions are also treated as values and used as data.

-Functions as first-class entities can:

-refer to it from constants and variables

-pass it as a parameter to other functions

-return it as result from other functions

-The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.

-When we talk about higher-order functions, we mean a function that either:

-takes one or more functions as arguments, or

-returns a function as its result.

-Given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection. Basically, if the callback expression is true, the filter function will include the element in the result collection. Otherwise, it will not.

-The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.

-The idea of reduce is to receive a function and a collection, and return a value created by combining the items.

## Refactoring JavaScript for Performance and Readability

-We're an URL-shortening website, like TinyURL. We accept a long URL and return a short URL that forwards visitors to the long URL.

