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

<h3> 3. ATM Withdrawal Logic 💳</h3>

**Description🔍**: This program simulates an ATM withdrawal system. It checks if the requested withdrawal amount can be processed based on the available account balance.

---

## Code📝
```python
print("\nWelcome to ATM Withdrawal System!!!\n")

# Input: Ask user for account balance and withdrawal amount
account_balance = float(input("Enter your account balance: "))
withdraw_amount = float(input("Enter the amount to withdraw: "))

# Check if withdrawal is possible
if withdraw_amount <= account_balance:
    # Update account balance
    account_balance -= withdraw_amount
    print(f"Transaction successful. \nRemaining balance: {account_balance:.2f}")
else:
    print("Insufficient balance.")
```

---

## Example Output📊

**Input:** 

`Enter your account balance: 5000`

`Enter the amount to withdraw: 2000`  

**Output:** 

`Transaction successful.`

`Remaining balance: 3000.00`

**Input:** 

`Enter your account balance: 3000`

`Enter the amount to withdraw: 4000`  

**Output:** 

`Insufficient balance.`

---

<h3> 4. Find Largest Among Three Numbers🔢</h3>

**Description🔍**: This program takes three numbers as input and determines the largest of the three.

---

## Code📝

```python
print("\nWelcome to Find the Largest Number!!!\n")
input_no1 = float(input("Enter your First number: "))
input_no2 = float(input("Enter your Second number: "))
input_no3 = float(input("Enter your Third number: "))

if input_no1 > input_no2:
    print(input_no1, "is the largest number.")
elif input_no2 > input_no3:
    print(input_no2, "is the largest number.")
else:
    print(input_no3, "is the largest number.")
```

## Example Output📊
**Input_01**: `5, 9, 3`

**Output**: `9 is the largest number.`

**Input_02**: `10, 8, 7`

**Output**: `10 is the largest number.`

**Input_03**: `4, 4, 2`

**Output**: `4 is the largest number.`

---

<h3> 5. Check Quadrant of a Point📍</h3>

**Description🔍**: This program takes the coordinates (x, y) of a point as input and determines which quadrant the point lies in or if it lies on an axis.

---

## Code📝
```python
print("\nWelcome to Check Point Quadrant!!!\n")
# Input: Ask user for coordinates
x = float(input("Enter the x-coordinate: "))
y = float(input("Enter the y-coordinate: "))
# 0 = zero & 1 = non-zero
# 🚀 Logic01 : 
# 1. (x,y) = (0,0) : Origin,             ✔️ Both value (x,y) are zero 
# 2. (x,y) = (1,0) : OriginOn x-axis,    ✔️ the value of x is non-zero AND the value of y is zero   
# 3. (x,y) = (0,1) : OriginOn y-axis,    ✔️ the value of x is zero AND the value of y is no-zero
# 🚀 Logic02 : 
# 1st_quadrant (+,+),    ✔️ Both value (x,y) are positive 
# 2nd_quadrant (-,+),    ✔️ if value of x is nagative and value of y is positive  
# 3rd_quadrant (-,-),    ✔️ Both value (x,y) are nageitive
# 4th_quadrant (+,-),    ✔️ if value of x is positive and value of y is nagetive
if x == 0 & y == 0:
    print("the point is at the Origin.")
elif y == 0:
    print("the point is at the Origin x-axis.")
elif x == 0:
    print("the point is at the Origin y-axis.")
elif x > 0 & y > 0:
    print("The point lies in the 1st Quadrant.")
elif x < 0 & y > 0:
    print("The point lies in the 2nd Quadrant.")
elif x < 0 & y < 0:
    print("The point lies in the 3rd Quadrant.")
elif x > 0 & y < 0:
    print("The point lies in the 4rt Quadrant.")
```



