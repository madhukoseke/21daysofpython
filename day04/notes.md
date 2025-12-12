# Day 4: Tuples & Sets

## 📚 Topics Covered
- Tuples (immutable sequences)
- Tuple unpacking
- Sets (unique collections)
- Set operations

## 🔑 Key Concepts

### Tuples
```python
empty = ()
single = (1,)  # Comma required!
coords = (10, 20)
mixed = (1, "hello", 3.14)

# Unpacking
x, y, z = (10, 20, 30)
```

### Tuple Methods
```python
my_tuple.count(item)  # Count occurrences
my_tuple.index(item)  # Find index
```

### Sets
```python
empty = set()  # NOT {}
numbers = {1, 2, 3, 4, 5}
unique = set([1, 2, 2, 3])  # {1, 2, 3}
```

### Set Operations
```python
set_a | set_b      # Union
set_a & set_b      # Intersection
set_a - set_b      # Difference
set_a ^ set_b      # Symmetric difference

set_a.add(item)    # Add element
set_a.remove(item) # Remove (raises error)
set_a.discard(item)# Remove (no error)
```

## ✅ Remember
- Tuples are immutable
- Single-item tuple needs comma: (1,)
- Sets only store unique values
- Sets are unordered
- Use sets for fast membership testing

## 📝 Practice Focus
- Tuple unpacking
- Set operations (union, intersection)
- Removing duplicates with sets
- When to use tuple vs list vs set
