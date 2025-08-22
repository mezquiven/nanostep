There are some cases where it is useful to shorten the code if it can be understood just fine.
```python
def add_two_num(num1, num2):
    return num1 + num2

result = 0
value1 = 0
value2 = 0

value1 = int(input("Enter first number: "))
value2 = int(input("Enter second number: "))

result = add_two_num(value1, value2)
print("The value is: ", result)
```


The code will become more readable if things are done one step at a time but it will need a lot of variables and takes a lot of lines. This approach is acceptable as long as you know what variables are already declared and which purpose they were created for.
```python
def add_two_num(num1, num2):
    return num1 + num2

result = 0
data1 = ""
data2 = ""
value1 = 0
value2 = 0

data1 = input("Enter first number: ")
value1 = int(data1)

data2 = input("Enter second number: ")
value2 = int(data2)

result = add_two_num(value1, value2)
print("The value is: ", result)
```

Instead of using another variable, we can update the values instead.
```python
def add_two_num(num1, num2):
    return num1 + num2

result = 0
value1 = 0
value2 = 0

value1 = input("Enter first number: ")
value1 = int(value1)
value2 = input("Enter second number: ")
value2 = int(value2)
result = add_two_num(value1, value2)
print("The value is: ", result)
```