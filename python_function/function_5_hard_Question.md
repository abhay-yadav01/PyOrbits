<h3> 🚀 Question 1: Recursive Function</h3>

**Description🔍**: Write a recursive function called factorial(n) that calculates the factorial of a given number n. Test the function with n = 5.

---

## Code📝
```python
# Recursive function to calculate factorial
def factorial(n):
    # Base case: factorial of 0 or 1 is 1
    if n == 0 or n == 1:
        return 1
    # Recursive case: n * factorial(n-1)
    else:
        return n * factorial(n - 1) 
# Calling the function and printing the result
number = 5
result = factorial(number)
print("The factorial of", number, "is", result)
```
---

## Example Output📊  
**Output:** ```The factorial of 5 is 120```

---

<h3> 🚀 Question 2: Function with Variable-Length Arguments</h3>

**Description🔍**: Create a function named calculate_average(*numbers) that takes any number of numeric arguments and returns their average. If no arguments are provided, return 0. Call the function with (10, 20, 30, 40) and without arguments.

---

## Code📝
```python
# Function to calculate the average
def calculate_average(*numbers):
    if len(numbers) == 0:  # Check if no arguments are provided
        return 0
    else:
        average = sum(numbers) / len(numbers)  # Calculate the average
        return average

# Calling the function with arguments
result1 = calculate_average(10, 20, 30, 40)
print("The average is:", result1)

# Calling the function without arguments
result2 = calculate_average()
print("The average is:", result2)
```

## Example Output📊  
**Output:** 
```
The average is: 25.0
The average is: 0
```

---
