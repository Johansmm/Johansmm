## Usage  
Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

Another example to use:
```python
from libraries.dynamics import spread_zombie_dynamics as szd
from libraries.dynamics import graph_by_default
import datetime as dt
import tqdm

G = graph_by_default(nodes = 20)
ini_date = dt.datetime(year = 2019, month = 8, day = 18)
dynamic = szd(graph = G, INTIAL_DATE = ini_date)
```
