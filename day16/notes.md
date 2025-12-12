# Day 16: Exception Handling

## 📚 Topics Covered
- try-except blocks
- Multiple except clauses
- finally clause
- Raising exceptions

## 🔑 Key Concepts

### Basic Try-Except
```python
try:
    # risky code
except Exception as e:
    # handle error
```

### Multiple Exceptions
```python
try:
    # code
except ValueError:
    # handle value error
except KeyError:
    # handle key error
```

### Finally Clause
```python
try:
    # code
except Exception:
    # handle error
finally:
    # always executes
```

### Raising Exceptions
```python
raise ValueError("Invalid value")
```

## ✅ Remember
- Catch specific exceptions
- Use finally for cleanup
- Don't catch all exceptions blindly
- Raise meaningful errors
- Exception hierarchy matters

## 📝 Practice Focus
- Handling common exceptions
- Input validation
- File operation errors
- Creating custom exceptions
