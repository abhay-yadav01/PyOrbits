<h3> 1. Basic Number Comparison🔢</h3>

**Description🔍**: This program takes a number as input and determines whether it is positive or non-positive.

---

## Code📝
```python
print("Welcome to Number Comparison !!!\n")
x = int(input("Enter your number: "))
if x > 0:
    print(x, "is a Positive number.")
else:
    print(x, "is a Non-Positive number.")
```

---

## Example Output📊
**Input:** `5`  
**Output:** `5 is a Positive number.`

**Input:** `-3`  
**Output:** `-3 is a Non-Positive number.`

**Input:** `0`  
**Output:** `0 is a Non-Positive number.`

---

<h3> 2. Even or Odd🔢</h3>

**Description🔍**: This program checks if a number is even or odd.

---

## Code📝
```python
print("\nWelcome to Even or Odd Number!!!\n")
number = int(input("Enter your number: "))
if number % 2 == 0:
    print(number, "is Even number.")
else:
    print(number, "is Odd number.")
```

---

## Example Output📊
**Input:** `4`  
**Output:** `4 is Even number.`

**Input:** `7`  
**Output:** `7 is Odd number.`

---

<h3> 3. Age Check🔢</h3>

**Description🔍**: This program asks for a user's age and checks if they are eligible to vote.

---

## Code📝
```python
print("\nWelcome to Age Check!!!\n")
age = int(input("Enter your Age: "))
if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")
```

---

## Example Output📊
**Input:** `20`  
**Output:** `You are eligible to vote.`

**Input:** `16`  
**Output:** `You are not eligible to vote.`

---

<h3> 4. Check for Discount🔢</h3>

**Description🔍**: This program checks if the user is eligible for a discount based on their shopping bill amount.

---

## Code📝
```python
print("\nWelcome to Discount Checker!!!\n")
bill_amount = int(input("Enter your total shopping bill amount: "))
if bill_amount >= 1000:
    print("You are eligible for a discount.")
else:
    print("No discount available.")
```

---

## Example Output📊
**Input:** `1500`  
**Output:** `You are eligible for a discount.`

**Input:** `800`  
**Output:** `No discount available.`

---

<h3> 5. Grade Checker🔢</h3>

**Description🔍**: This program checks if the entered marks are sufficient to pass or fail.

---

## Code📝
```python
print("\nWelcome to Grade Checker!!!\n")
marks = int(input("Enter your Marks: "))
if marks >= 50:
    print("Pass")
else:
    print("Fail")
```

---

## Example Output📊
**Input:** `75`  
**Output:** `Pass.`

**Input:** `45`  
**Output:** `Fail.`
