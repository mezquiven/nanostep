Creating a function helps us reuse code and saves us time of typing long lines of code.
For example, if I want to display three different print statements and then repeat the pattern four times, it will become a very long code.

```python
print("A new game is in development and is estimated to be released next year.")
print("There is this awesome documentary about wolves online.")
print("Italian pasta is awesome.")

print("A new game is in development and is estimated to be released next year.")
print("There is this awesome documentary about wolves online.")
print("Italian pasta is awesome.")

print("A new game is in development and is estimated to be released next year.")
print("There is this awesome documentary about wolves online.")
print("Italian pasta is awesome.")

print("A new game is in development and is estimated to be released next year.")
print("There is this awesome documentary about wolves online.")
print("Italian pasta is awesome.")
```

With functions, things can become readable and we won't need to type a very long code. Any code that is indented becomes the block that makes up the function. Unindented code are not included to the function. The function definition is like declaring a function while the function call is the actual execution of the code inside the function.

```python
# function definition
def display_message():
    print("A new game is in development and is estimated to be released next year.")
    print("There is this awesome documentary about wolves online.")
    print("Italian pasta is awesome.")

# function calls
display_message()
display_message()
display_message()
display_message()
```