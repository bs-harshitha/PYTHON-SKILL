# 🔄 Input and Output in Python

## 📘 Introduction

In Python, **input** is used to take data from the user.  


---

## ⌨️ Input in Python

Python uses the `input()` function to take user input.

### 🔹 Syntax
  ```python
  variable_name = input("Enter something: ")
```
### NOTE:
  - input() take the data as string.
  - if u want input in numerical form u can use int(), float().

## Example :
1.Normal form
```python
 name_str = input("Enter your name: ")
print("Hello", name)
```

2.Numerical form
```python
 age = int(input("Enter your age: "))
print("Your age is", age)

```

## 📘 Introduction

In Python, **output** is used to display data to the user.
it uses print( ).

---

### 🔹 Syntax
  ```python
  print(value)

```
### Example
  ```python
  print(10)

```

## Formatting Output types:

### 1.Using Comma (,) :
  ```python
 name = "John"
age = 21
print("Name:", name, "Age:", age)


```

### 2.Using f-Strings (⭐⭐⭐) :
  ```python
name = "John"
age = 21
print(f"My name is {name} and I am {age} years old.")

```
---
# 🔄 Summary

## ⌨️ Input
- `input()` is used to take data from the user.
- `print()`is used to give output .




