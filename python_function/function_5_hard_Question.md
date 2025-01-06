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
