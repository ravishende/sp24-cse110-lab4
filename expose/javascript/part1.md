# Part 1

1. `values added: 20`
2. `final result: 20`
3. `values added: 20`
4. There is an error: `result is not defined` at line 8
   - This is because result isn't defined in line 8. This is because let is only defining `result` within the scope of the if block, so outside the if, it is undefined.
5. There is an error: `TypeError: Assignment to constant variable.` at line 4.
   - This is because result is declared as a constant, so when we try to redefine it with `result = num1 + num2`, it throws an error, saying you can't redefine it.
