# Day 1: Variables & Data Types

## 📚 Topics Covered
- Variables and variable naming
- Data types: int, float, str, bool
- Type conversion
- Basic operations

## 🔑 Key Concepts

### Variable Assignment
```python
name = "Alice"
age = 25
height = 1.65
is_student = True
result = None
```

### Data Types
- **int**: Whole numbers (5, -10, 1000)
- **float**: Decimal numbers (3.14, -0.5, 2.0)
- **str**: Text ("hello", 'Python')
- **bool**: True or False
- **NoneType**: Represents the absence of a value (None)




### Type Conversion
```python
int("42")      # String to integer
float("3.14")  # String to float
str(100)       # Integer to string
```

### Multiple Assignment
```python
x, y, z = 10, 20, 30
a = b = c = 100
```

## 💡 Quick Reference

### Checking Type
```python
type(variable)  # Returns the data type
```

### Common Operations
```python
# Arithmetic
a + b, a - b, a * b, a / b
a // b  # Floor division
a % b   # Modulus
a ** b  # Exponentiation

# String concatenation
first_name + " " + last_name
```

## ✅ Remember
- Variable names are case-sensitive
- Use descriptive names (snake_case)
- Cannot start with a number
- Python is dynamically typed
- Use type() to check data types
- Use f-strings for formatting: f"Value: {variable}"

## 📝 Practice Focus
- Creating variables of different types
- Type conversion between int, float, str
- Using variables in calculations
- String formatting with f-strings
