There are many ways to name something.
```
player_health
customerName
AddTwoNumbers
GRAVITY
```

In C or Python, variable names are usually named just like in the first example. So variable names can be customer_age, student_address, employee_id and so on. In C#, C++ and other programming languages, the second example is used in naming variables and the third one is used for functions. Different cases for different names can be helpful in identifying if the name is used for a variable, function, class, etc.

In C, using a variable name with all of its characters in uppercase is used for a constant value. It means that the variable is not going to change in value later on. It can be used for variables like gravity or pi. This is just a convention so it is up to you if you will follow it or not.

```python
GRAVITY = 9.8
PI = 3.14

print("The value of gravity is: ", GRAVITY)
print("The value of pi is: ", PI)
```

The indentation can be a tab character or actual spaces depending on the settings you use on your code editor. In my opinion, 4 spaces as the size for tabs is ideal while 2 spaces is good for HTML. You can try to experiment with 2, 3 or 4 spaces as the size and choose the one you are comfortable with. Just make sure that you use the same size to everything.

Code can be written in different styles. A C++ code can be written as:
```cpp

int add_two_numbers(int num1, int num2)
{
    int value = 0;
    value = num1 + num2;
    return value;
}

int main()
{
    int number1 = 0, number2 = 0;

    cout<<"Enter the first number: ";
    cin>>number1;
    cout<<"Enter the second number: ";
    cin>>number2;

    result = add_two_numbers(number1, number2);

    cout<<"The value is: "<<result;
}
```

Another style for C++ which can save space by using less lines is:
```cpp

int add_two_numbers(int num1, int num2) {
    int value = 0;
    value = num1 + num2;
    return value;
}

int main() {
    int number1 = 0, number2 = 0;

    cout<<"Enter the first number: ";
    cin>>number1;
    cout<<"Enter the second number: ";
    cin>>number2;

    result = add_two_numbers(number1, number2);

    cout<<"The value is: "<<result;
}
```

Python uses indentation to know which lines of code are part of a function or not but we can also apply the use of empty lines to make the code readable.

Fewer lines is needed when we combine calculation together.
```python
num1 = 32
num2 = 85
print("The value is: ", num1 + num2)
```

More lines is needed if we want to divide larger chunks into smaller chunks but is more readable.
```python

num1 = 32
num2 = 85
result = 0

result = num1 + num2
print(`The value is: {result}`)
```

Using longer variable names can sometimes help in readability. A short variable name can be confusing.
```python
n1 = 32
n2 = 85
res = 0

res = n1 + n2
print(`The value is: {res}`)
```