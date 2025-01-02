<h3> 1. Nested Conditions with Marks🔢</h3>

**Description🔍**: This program calculates the percentage based on total marks and assigns a grade based on nested conditions.

---

## Code📝
```python
print("\nWelcome to Marks Grading System!!!\n")
total_marks = float(input("Enter your total marks out of 500: "))
percentage = (total_marks / 500) * 100
if percentage > 90:
    print("Grade: A+")
elif 75 <= percentage <= 90:
    print("Grade: A")
elif 50 <= percentage < 75:
    print("Grade: B")
else:
    print("Grade: Fail")
```

---

## Example Output📊
**Input:** `450`  
**Output:** `Grade: A+.`

**Input:** `380`  
**Output:** `Grade: A.`

**Input:** `260`  
**Output:** `Grade: B.`

**Input:** `180`  
**Output:** `Grade: Fail.`

---

<h3> 2. Check Leap Year 📅</h3>

**Description🔍**: This program checks whether a given year is a leap year or not based on specific conditions.

---

## Code📝
```python
print("\nWelcome to Leap Year Checker!!!\n")
year = int(input("Enter a year: "))

if (year % 400 == 0):
    print(f"{year} is a leap year.")
elif (year % 100 == 0):
    print(f"{year} is not a leap year.")
elif (year % 4 == 0):
    print(f"{year} is a leap year.")
else:
    print(f"{year} is not a leap year.")
```

---

## Example Output📊
**Input:** `2000`  
**Output:** `2000 is a leap year.`

**Input:** `1900`  
**Output:** `1900 is not a leap year.`

**Input:** `2024`  
**Output:** `2024 is a leap year.`

**Input:** `2023`  
**Output:** `2023 is not a leap year.`

---

