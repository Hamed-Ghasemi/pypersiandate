# pypersiandate

Python library for converting gregorian date to persian date.

# Install
`pip install pypersiandate`
# Usage
```python
from pypersiandate.pypersiandate import *
res = topersia(2020,1,1)
print(res['day'])
print(res['dayname'])
print(res['year'])
print(res['month'])
print(res['monthname'])
```
