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

---

<h3> 3. Grade Assignment🔢</h3>

**Description🔍**: This program takes a score (out of 100) as input and assigns grades based on defined ranges.

---

## Code📝
```python
print("\nWelcome to Grade Assignment!!!\n")
score = int(input("Enter your Score out of 100: "))
if score >= 90:
    print("You achieved Grade A")
elif 80 <= score <= 89:
    print("You achieved Grade B")
elif 70 <= score <= 79:
    print("You achieved Grade C")
else:
    print("You Failed")
```

---

## Example Output📊
**Input:** `92`  
**Output:** `You achieved Grade A.`

**Input:** `85`  
**Output:** `You achieved Grade B.`

**Input:** `72`  
**Output:** `You achieved Grade C.`

**Input:** `65`  
**Output:** `You Failed.`

---

<h3> 4. Triangle Validity Checker🔢</h3>

**Description🔍**: This program checks if three sides can form a valid triangle based on triangle inequality rules.

---

## Code📝
```python
print("\nWelcome to Triangle Validity Checker!!!\n")
side1 = float(input("Enter the first side of the triangle: "))
side2 = float(input("Enter the second side of the triangle: "))
side3 = float(input("Enter the third side of the triangle: "))
# Check for triangle validity
if (side1 + side2 > side3) and (side1 + side3 > side2) and (side2 + side3 > side1):
    print("The triangle is valid.")
else:
    print("The triangle is not valid.")
```

---

## Example Output📊
**Input:** `3, 4, 5`  
**Output:** `The triangle is valid.`

**Input:** `1, 2, 3`  
**Output:** `The triangle is not valid.`

---

<h3> 5. Login System🔢</h3>

**Description🔍**: This program validates user credentials for login.

---

## Code📝
```python
print("\nWelcome to Login System!!!\n")
username = input("Enter your username: ")
password = input("Enter your password: ")
if username == "admin" and password == "password123":
    print("Access granted.")
else:
    print("Access denied.")
```

---

## Example Output📊
**Input:** `admin, password123`  
**Output:** `Access granted.`

**Input:** `user, pass`  
**Output:** `Access denied.`
