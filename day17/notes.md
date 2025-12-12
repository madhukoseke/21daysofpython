# Day 17: Modules & Packages

## 📚 Topics Covered
- Importing modules
- Creating modules
- pip package manager
- Standard library overview

## 🔑 Key Concepts

### Importing
```python
import math
from math import sqrt
import math as m
from module import *  # avoid this
```

### Creating Modules
```python
# mymodule.py
def my_function():
    pass

# main.py
import mymodule
mymodule.my_function()
```

### Using pip
```bash
pip install package_name
pip install -r requirements.txt
pip list
pip uninstall package_name
```

## ✅ Remember
- Modules organize code
- Standard library is extensive
- Use virtual environments
- import runs the module
- __name__ == "__main__" pattern

## 📝 Practice Focus
- Using standard library
- Creating your own modules
- Installing packages with pip
- Organizing larger projects
