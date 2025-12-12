# Day 3: Lists

## 📚 Topics Covered
- Creating and accessing lists
- List methods (append, insert, remove, pop)
- List slicing
- Sorting and reversing

## 🔑 Key Concepts

### Creating Lists
```python
empty = []
numbers = [1, 2, 3, 4, 5]
mixed = [1, "hello", 3.14, True]
```

### Accessing Elements
```python
my_list[0]      # First element
my_list[-1]     # Last element
my_list[1:4]    # Slice
```

### Modifying Lists
```python
my_list.append(item)      # Add to end
my_list.insert(index, item)  # Insert at position
my_list.remove(item)      # Remove first occurrence
my_list.pop()             # Remove and return last
my_list.pop(index)        # Remove at index
```

### List Operations
```python
my_list.sort()       # Sort in place
my_list.reverse()    # Reverse in place
sorted(my_list)      # Return sorted copy
len(my_list)         # Length
my_list.count(item)  # Count occurrences
my_list.index(item)  # Find index
```

## ✅ Remember
- Lists are mutable (can be changed)
- Indexing starts at 0
- Negative indices work backwards
- append() vs extend() vs insert()
- sort() modifies, sorted() returns new list

## 📝 Practice Focus
- List manipulation methods
- Slicing techniques
- Finding max/min without built-ins
- Removing duplicates
