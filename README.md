# tmpy.crr

Tiny Python package providing simple coordinate rotation and reflection helpers.

## Installation

Install from source (branch `tmpy-crr-layout`):

```bash
pip install git+https://github.com/TMR-Mark/TMRpy.git@tmpy-crr-layout
```

## Usage

```python
from tmpy import rotate_point, reflect_point

p = (1.0, 0.0)
rotated = rotate_point(p, 3.14159/2)  # rotate 90 degrees CCW
reflected = reflect_point(p, axis="y")  # reflect across y-axis
```

## Project layout

- pyproject.toml — project metadata and build configuration
- README.md — this file
- src/tmpy/
  - __init__.py
  - crr.py

License: MIT