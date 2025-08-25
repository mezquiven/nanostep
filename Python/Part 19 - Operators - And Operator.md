When we want to combine two or more conditions, we can use the && symbol.

We can specify a range that is acceptable by using &&.
```python
age = 20

if age >= 18 && age <= 30:
	print("The new MMORPG game that will be released next year is targeted to players ages 18 to 30 years old.")
```

When age is 17 or below and 31 or above, print function won't execute. Both must be true when using && or if there are three or more conditions, all must be true to execute the print function.
```python
age = 15

if age >= 18 && age <= 30:
	print("The new MMORPG game that will be released next year is targeted to players ages 18 to 30 years old.")
```