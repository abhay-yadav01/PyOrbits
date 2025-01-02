<h3> 1. Print Numbers from 1 to 10 🔢</h3>

**Description🔍**: This program uses a for loop to print numbers sequentially from 1 to 10.

---

## Code📝
```python
for i in range(1,11):
    print(i)
```

---

## Example Output📊
**Output:** 
`
1
2
3
4
5
6
7
8
9
10
`

---

<h3> 2. Print Each Character in a String 🔠</h3>

**Description🔍**: This program takes a string as input and uses a for loop to iterate through each character in the string. It prints each character on a new line, demonstrating the use of loops for string traversal. 

---

## Code📝
```python
string = str(input("Enter Your string : "))
for character in string:
    print(character)
```
---
## Example Output📊
**Input**: `python is good.`

**Output:** 
`
p
y
t
h
o
n
`
`
i
s
`
`
g
o
o
d
`

---

<h3> 3. Sum of Numbers in a List🔠</h3>

**Description🔍**: This program takes a list of numbers as input and calculates the sum of all the numbers in the list.

---

## Code📝
```python
numbers = [1, 2, 3, 4, 5]
total_sum = 0
for number in numbers:
    total_sum += number
    print("The sum of the numbers in the list is:", total_sum)
```

---

## Example Output📊
**Output:** `15`

---

<h3> 4. Print Even Numbers in a Range 🔢</h3>

**Description🔍**: To desplay Even numbers between 1 and 20.

---

## Code📝
```python
print("Even numbers between 1 and 20 are:")
for number in range(1, 21):
    if number % 2 == 0:  # Check if the number is even
        print(number)
```
---
