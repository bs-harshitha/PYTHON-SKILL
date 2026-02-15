# 📘 Operators in Python 

##  Introduction
Operators are  symbols used to perform operations on variables and values.

---

##  1️ Arithmetic Operators
Used to perform mathematical operations.

| Operator | Meaning            | Example         |
|----------|-------------------|------------------|
| `+`      | Addition          | 5 + 3 =8         |
| `-`      | Subtraction       | 5 - 3 = 2        |
| `*`      | Multiplication    | 5 * 3 = 15       |
| `/`      | Division          | 5 / 2 = 2.5      |
| `//`     | Floor Division    | 5 // 2 = 2       |
| `%`      | Modulus (Remainder)| 5 % 2 = 1       |
| `**`     | Exponent          | 2 ** 3 =(2 * 2 * 2)=8|

Example:
```python
a = 10
b = 3
print(a + b)
print(a % b)
```

##   2️ Comparison Operators
Used to compare between two values.


| Operator | Meaning                  |
| -------- | ------------------------ |
| `==`     | Equal to                 |
| `!=`     | Not equal to             |
| `>`      | Greater than             |
| `<`      | Less than                |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to    |

Example:
```python
x = 5
y = 10
print(x < y)
```

## 3️ Logical Operators
 combine conditional statements.

| Operator | Meaning                                |
| -------- | -------------------------------------- |
| `and`    | True if both conditions are true       |
| `or`     | True if at least one condition is true |
| `not`    | Reverses the result                    |

Example:
```python
a = 5
print(a > 2 and a < 10)

```
##  4️ Assignment Operators

 assign values.
 
| Operator | Example |
| -------- | ------- |
| `=`      | x = 5   |
| `+=`     | x += 3  |
| `-=`     | x -= 3  |
| `*=`     | x *= 3  |
| `/=`     | x /= 3  |

Example:
```python
a = 5
print(a)

```
## 5️ Membership Operators (mostly usedin loops)
used to check whether value exist or not.
| Operator | Meaning                 |
| -------- | ----------------------- |
| `in`     | Present in sequence     |
| `not in` | Not present in sequence |

Example:
```python
nums = [1, 2, 3]
print(2 in nums)

```
## 6️ Identity Operators
to compare memory location
| Operator | Meaning         |
| -------- | --------------- |
| `is`     | Same object     |
| `is not` | Not same object |

Example:
```python
a = 5
b = 5
print(a is b)

```
