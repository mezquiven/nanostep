When using the != symbol, it is important to know that there are many possible values that are true.

For example, let's make the number 100 the integer we will focus on. Any numbers like -4, 8, 72, 99, 101, 250 and so on will make the condition true.
```python
num1 = 0

if num1 != 100:
    print("When Fast Boot is enabled in a computer, it can be hard to go into the BIOS settings.")
```

Only when num1 is 100 will the condition become false.
```python
num1 = 100

if num1 != 100:
    print("When Fast Boot is enabled in a computer, it can be hard to go into the BIOS settings.")
```