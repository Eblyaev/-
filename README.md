# Python
```python
from scriptcontext import sticky
import math


if start == True:
    sticky["x"] = 0
    sticky["y"] = 0
    sticky["z"] = 0
else:
    sticky["x"] = sticky["x"] + 0.1
    sticky["y"] = sticky["y"] + 0.1
    sticky["z"] = sticky["z"] + 0.1

a = 10*math.cos(sticky["x"])
b = 10*math.sin(sticky["y"])
c = sticky["z"]
```
