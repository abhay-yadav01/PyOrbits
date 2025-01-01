<h3> 1. Number Range Check🔢</h3>

**Description🔍**: This program asks the user for a number and checks if it is within the range of 10 to 50 (inclusive).

---

## Code📝
```python
print("\nWelcome to Number Range Check!!!\n")
number = int(input("Enter your Number: "))
if 10 <= number <= 50:
    print("Number is in range.")
else:
    print("Number is out of range.")
```

---

## Example Output📊
**Input:** `25`  
**Output:** `Number is in range.`

**Input:** `5`  
**Output:** `Number is out of range.`

---

<h3> 2. Multiple Conditions🔢</h3>

**Description🔍**: This program checks if a number is divisible by both 3 and 5, only 3, only 5, or neither.

---

## Code📝
```python
print("\nWelcome to Multiple Conditions Checker!!!\n")
div_number = int(input("Enter your number: "))
if div_number % 3 == 0 and div_number % 5 == 0:
    print("FizzBuzz.")
elif div_number % 3 == 0:
    print("Fizz.")
elif div_number % 5 == 0:
    print("Buzz.")
else:
    print(div_number)
```

---

## Example Output📊
**Input:** `15`  
**Output:** `FizzBuzz.`

**Input:** `9`  
**Output:** `Fizz.`

**Input:** `10`  
**Output:** `Buzz.`

**Input:** `7`  
**Output:** `7.`
