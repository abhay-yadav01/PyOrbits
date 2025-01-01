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

