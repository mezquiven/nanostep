If we want to pass a value to the function, we can add a variable name near the function name in the function definition. We can treat this variable name as declaring a new variable that is a local variable and is only accessible inside the function definition. The value from the function call will be copied by the local variable.
```python
def square_one_number(number):
    return number * number

result = 0
result = square_one_number(56)

print(`The value is: {result}`)
```