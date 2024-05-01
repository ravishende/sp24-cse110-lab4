# Dev Tools Part 2

1. The bug was that num1 and num2 were collected as strings, so result was the concatenation of 2 strings rather than the addition of 2 numbers. Also, none of the lines in calculateSum had semicolons.
2. I fixed it by adding `parseInt()` around num1 and num2 to create the following line: `let result = parseInt(num1) + parseInt(num2);`
