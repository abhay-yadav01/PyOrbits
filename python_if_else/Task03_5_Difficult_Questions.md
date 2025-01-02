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

---

**Input:** 

`Enter your account balance: 3000`

`Enter the amount to withdraw: 4000`  

**Output:** 

`Insufficient balance.`

