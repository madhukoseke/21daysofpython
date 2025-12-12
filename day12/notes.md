# Day 12: Functions Advanced

## 📚 Topics Covered
- Default parameters
- *args and **kwargs
- Lambda functions
- Function documentation

## 🔑 Key Concepts

### Default Parameters
```python
def greet(name, greeting="Hello"):
    return f"{greeting}, {name}!"
```

### *args (Variable Arguments)
```python
def sum_all(*args):
    return sum(args)

sum_all(1, 2, 3, 4)
```

### **kwargs (Keyword Arguments)
```python
def print_info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")
```

### Lambda Functions
```python
square = lambda x: x ** 2
add = lambda a, b: a + b
```

## ✅ Remember
- Default parameters go last
- *args collects positional arguments
- **kwargs collects keyword arguments
- Lambda for simple one-liners
- Use docstrings for documentation

## 📝 Practice Focus
- Flexible function parameters
- Lambda expressions
- Higher-order functions
- Function documentation
