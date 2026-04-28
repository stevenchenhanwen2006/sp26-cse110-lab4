1. The bug is that when the user inputs two numbers, javascript treats the inputs as strings, so
   the function calculateSum() does string concatenation instead of mathematical addition.
2. To fix this issue, we convert num1 and num2 to number type when adding to result.