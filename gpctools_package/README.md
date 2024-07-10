# gpctools

A package for common use tools by the Dev team at GP Joule Connect.

## Tools:
. Decorators:
- exectime: decorator that prints the execution time of a function 

## Installation:

```bash
pip install gpctools
```

## Usage:
- exectime:
```python
from gpctools.decorators import exectime

@exectime
def function_x():
    """function code"""

# prints to console: exectime: function_x() took [number of seconds, with 3 decimals]s to run.
```




