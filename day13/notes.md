# Day 13: List Comprehensions

## 📚 Topics Covered
- List comprehension syntax
- Filtering with conditions
- Nested comprehensions
- Dict and set comprehensions

## 🔑 Key Concepts

### Basic List Comprehension
```python
squares = [x**2 for x in range(10)]
```

### With Condition
```python
evens = [x for x in range(10) if x % 2 == 0]
```

### Nested Comprehension
```python
matrix = [[i*j for j in range(3)] for i in range(3)]
```

### Dictionary Comprehension
```python
{x: x**2 for x in range(5)}
```

### Set Comprehension
```python
{x for x in [1, 2, 2, 3, 3]}
```

## ✅ Remember
- More concise than loops
- Format: [expression for item in iterable if condition]
- Don't overuse (readability matters)
- Works for lists, dicts, sets
- Can replace map() and filter()

## 📝 Practice Focus
- Converting loops to comprehensions
- Filtering data
- Data transformations
- Readability vs conciseness
