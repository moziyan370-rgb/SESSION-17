[README_SESSION_17.md](https://github.com/user-attachments/files/32087665/README_SESSION_17.md)
# Session 17

## Example 1

```python
import math

num = 5

print("Square Root:", math.sqrt(num))
print("Factorial:", math.factorial(num))
print("Value of Pi:", math.pi)
```

**Output:**

```text
Square Root: 2.23606797749979
Factorial: 120
Value of Pi: 3.141592653589793
```

## Example 2

```python
import os

files = os.listdir()

for file in files:
    if file.lower().endswith(".jpg") or file.lower().endswith(".png"):
        print(file)
```

## Example 3

```python
from datetime import datetime

date_input = input("Enter date (YYYY-MM-DD): ")

date = datetime.strptime(date_input, "%Y-%m-%d")

print("Day:", date.strftime("%A"))
```

**Output:**

```text
Enter date (YYYY-MM-DD): 2026-09-11
Day: Friday
```

## Example 4

```python
def format_follower_count(n):
    if n >= 1000000:
        return f"{n / 1000000:.1f}M"
    elif n >= 1000:
        return f"{n / 1000:.1f}K"
    else:
        return str(n)
```

## Example 5

```python
import statistics

numbers = [10, 20, 30, 40, 50]

average = statistics.mean(numbers)

print("Average:", average)
```

**Output:**

```text
Average: 30
```
