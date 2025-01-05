<h3> 🚀 Question 1: Basics of Function Definition</h3>

**Description🔍**: Write a function named greet() that prints "Hello, World!". Then, call the function.

---

## Code📝
```python
def greet():
    print("Hello, World!")

# Calling the function
greet()
```
---

## Example Output📊  
**Output:** ```Hello, World!```

---

<h3>🚀 Question 2: Functions with Parameters</h3>

**Description🔍**: Create a function called add_numbers(a, b) that takes two parameters and prints their sum. Call the function with the values 5 and 10.

---

## Code📝
```python
def add_numbers(a,b):
    sum = a + b
    print("the sum of", a, "&", b, "=", sum)
# Calling the function
add_numbers(5,10)
```
---

## Example Output📊  
**Output:** ```the sum of 5 & 10 = 15```

---

<h3>🚀 Question 3: Functions with Return Values</h3>

**Description🔍**: Define a function named square(num) that returns the square of a given number. Call the function with 4 and print the result.

---

## Code📝
```python
def square(num):
    a = num * num 
    print("The Squrae of", num, "=", a)
# Calling the function    
square(4)
```
## Or
```python
def square(num):
    return num * num
# Calling the function and printing the result
result = square(4)
print("The Square of 4 =", result)
```
## Example Output📊  
**Output:** ```The Squrae of 4 = 16```

---

<h3>🚀 Question 4: Default Parameters</h3>

**Description🔍**: Write a function called introduce(name, age=18) that prints "My name is [name] and I am [age] years old.". Call the function once by providing both arguments and another time by providing only the name.

---
## Code📝
```python
def introduce(name, age=18):
    print("My name is", name, "and I am", age, "years old.")
# Calling the function
# in introduce(name, age=18) only "age" is Default Parameters
introduce("abhay",23) # name & age both are given
introduce("sanjay")   # name is given and age is not given 
# introduce() 
```

## Example Output📊  
**Output:** 
```
My name is abhay and I am 23 years old.
My name is sanjay and I am 18 years old.
```

---

<h3>🚀 Question 5: Function with Keyword Arguments</h3>

**Description🔍**: Create a function named describe_pet(animal_type, pet_name) that prints "I have a [animal_type] named [pet_name].". Call the function using keyword arguments animal_type='dog' and pet_name='Buddy'.

---
## Code📝
```python
def describe_pet(animal_type, pet_name):
    print("I have a", animal_type, "named", pet_name)
# Calling the function
describe_pet(animal_type="Dog", pet_name="Buddy") #Function calling with Keyword Arguments
describe_pet("Cat","minu") #Function calling without Keyword Arguments
```

## Example Output📊  
**Output:** 
```
I have a Dog named Buddy
I have a Cat named minu
```

---
