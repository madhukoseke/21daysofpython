# Day 9: For Loops

## 📚 Topics Covered
- For loop syntax
- range() function
- Iterating through sequences
- enumerate() and zip()
- Nested loops

## 🔑 Key Concepts

### Basic For Loop
```python
for item in sequence:
    # code
```

### Using range()
```python
range(stop)            # 0 to stop-1
range(start, stop)     # start to stop-1
range(start, stop, step)
```

### Iterating Lists
```python
for fruit in fruits:
    print(fruit)
```

### enumerate()
```python
for index, item in enumerate(my_list):
    print(f"{index}: {item}")
```

### Dictionary Iteration
```python
for key, value in my_dict.items():
    print(f"{key}: {value}")
```

### Nested Loops
```python
for i in range(3):
    for j in range(3):
        print(i, j)
```

## ✅ Remember
- For loops iterate over sequences
- range() generates numbers
- enumerate() gives index and value
- Use items() for dict iteration
- break exits loop, continue skips iteration

## 📝 Practice Focus
- Iterating different data types
- Using range() effectively
- Nested loop patterns
- List comprehensions (preview)
