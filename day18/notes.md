# Day 18: Working with Dates

## 📚 Topics Covered
- datetime module
- Creating date objects
- Formatting dates
- Date arithmetic

## 🔑 Key Concepts

### Importing datetime
```python
from datetime import datetime, date, timedelta
```

### Current Date/Time
```python
now = datetime.now()
today = date.today()
```

### Creating Dates
```python
d = date(2024, 12, 25)
dt = datetime(2024, 12, 25, 14, 30)
```

### Formatting
```python
now.strftime("%Y-%m-%d")
datetime.strptime("2024-12-25", "%Y-%m-%d")
```

### Date Arithmetic
```python
tomorrow = today + timedelta(days=1)
week_ago = today - timedelta(weeks=1)
```

## ✅ Remember
- datetime vs date vs time
- strftime = format to string
- strptime = parse from string
- timedelta for arithmetic
- Timezone awareness

## 📝 Practice Focus
- Date calculations
- Formatting dates
- Age calculators
- Schedule builders
