# Day 15: File Handling

## 📚 Topics Covered
- Reading files
- Writing files
- with statement
- CSV files

## 🔑 Key Concepts

### Reading Files
```python
with open('file.txt', 'r') as f:
    content = f.read()
    # or
    lines = f.readlines()
    # or
    for line in f:
        print(line)
```

### Writing Files
```python
with open('file.txt', 'w') as f:
    f.write('Hello\n')
    
# Append mode
with open('file.txt', 'a') as f:
    f.write('World\n')
```

### File Modes
- 'r': Read (default)
- 'w': Write (overwrites)
- 'a': Append
- 'r+': Read and write

## ✅ Remember
- Always use with statement
- File must exist for reading
- 'w' mode overwrites files
- readlines() returns list
- Close files (with does it automatically)

## 📝 Practice Focus
- Reading and parsing files
- Writing data to files
- Processing CSV files
- Error handling with files
