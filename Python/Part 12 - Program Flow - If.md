In program flow, we can use an if statement to change the direction of where the program is going to run. The if statement will check if the requirements based on the condition inside it are met. If all are true, it will execute the code inside it. If the condition is false, it will skip the code inside the if statement.

The condition inside the if statement is false.
```python
age = 20

if age < 18:
    print("You are not allowed to drive a car yet.")

print("The age variable was checked.")
```

The condition inside the if statement is true.
```python
age = 17

if age < 18:
    print("You are not allowed to drive a car yet.")

print("The age variable was checked.")
```

Multiple conditions can be combined.
```python
player_health = 100
player_level = 36
player_class = "assassin"

if player_health <= 25 && player_level >= 20 && player_class == "mage":
    print("Welcome to the Forbidden Library of Hellscythe.")
```

We can also use a single value or a single variable and nothing else to check if it is true or not.
```python
if True:
    print("This will execute because the condition is true.")
```

We can use the variable to check states.
```python
is_player_still_alive = 0

if is_player_still_alive:
    print("The player is still alive.")
```
