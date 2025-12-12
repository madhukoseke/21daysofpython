# Day 2: Strings

## 📚 Topics Covered
- String creation and manipulation
- String indexing and slicing
- String methods
- String formatting

## 🔑 Key Concepts

### Creating Strings
```python
single = 'Hello'
double = "World"
multiline = '''Multiple
lines'''
```

### Indexing & Slicing
```python
text = "Python"
text[0]      # First character: 'P'
text[-1]     # Last character: 'n'
text[0:3]    # Slice: 'Pyt'
text[::-1]   # Reverse: 'nohtyP'
```

### Common String Methods
```python
text.upper()       # Uppercase
text.lower()       # Lowercase
text.strip()       # Remove whitespace
text.split()       # Split into list
text.replace(old, new)  # Replace
text.find(substring)    # Find position
text.count(char)   # Count occurrences
```

### String Formatting
```python
# f-strings (recommended)
f"Hello {name}, you are {age} years old"

# Format method
"Hello {}, you are {}".format(name, age)
```

## ✅ Remember
- Strings are immutable
- Use f-strings for modern formatting
- Negative indices count from the end
- slice[start:end:step]
- Methods don't modify original string

## 📝 Practice Focus
- String slicing techniques
- Using string methods
- F-string formatting
- String concatenation vs joining
