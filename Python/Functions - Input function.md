The input function is used to get a value from the user.
```python
name = ""

name = input("Enter your name: ")
print("Name is: ", name)
```

The input function will give us a value of string data type so we should change the data type to integer if we are going to use the value in computations. We can also use a variable to store our string that will ask the user for input.
```python
message = "Enter a number: "
data = ""
number = 0

data = input(message)
number = int(data)
print("The number is: ", number)
```
