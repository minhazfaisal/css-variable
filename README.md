# css-variable

We can use CSS variables to maintain reusable CSS content like color, font family, background-color etc.

syntax - var(--name, value)

name - Required. The variable name must start with two dashes.
value -	Optional. The fallback value used if the variable is not found.

note - The variable name must begin with two dashes (--) and it is case sensitive!

CSS variables can have a global or local scope.

Global variables can be used through the entire document. To create a variable with global scope, declare it inside the :root selector.

Local variables can be used only inside the selector where it is declared.




