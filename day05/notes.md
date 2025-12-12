# Day 5: Dictionaries

## 📚 Topics Covered
- Dictionary basics (key-value pairs)
- Accessing and modifying dictionaries
- Dictionary methods
- Nested dictionaries

## 🔑 Key Concepts

### Creating Dictionaries
```python
empty = {}
person = {"name": "Alice", "age": 25}
```

### Accessing Values
```python
person["name"]          # Direct access
person.get("name")      # Safe access
person.get("key", default)  # With default
```

### Modifying Dictionaries
```python
person["city"] = "Boston"  # Add/update
del person["age"]          # Delete
person.pop("name")         # Remove and return
person.clear()             # Remove all
```

### Dictionary Methods
```python
dict.keys()       # All keys
dict.values()     # All values
dict.items()      # Key-value pairs
dict.update(other)# Merge dictionaries
```

### Iterating
```python
for key in my_dict:
    print(key)

for key, value in my_dict.items():
    print(f"{key}: {value}")
```

## ✅ Remember
- Keys must be unique and immutable
- Use get() to avoid KeyError
- Dictionaries maintain insertion order (Python 3.7+)
- Fast lookups by key
- items() returns (key, value) tuples

## 📝 Practice Focus
- Creating and accessing dictionaries
- Iterating through key-value pairs
- Nested dictionaries
- Dictionary comprehensions
