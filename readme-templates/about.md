<!-- ABOUT THE PROJECT -->
## About The Project

<a href="https://example.com"> <img src="images/screenshot.png"></a>

There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need -- I think this is it.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have have contributed to expanding this template!

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section lists the main frameworks and libraries used in the project.
* [python](https://rasa.com/)
* [networkx](https://networkx.org/)
* [matplotlib](https://matplotlib.org/)
* [opencv](https://opencv.org/)

<!-- GETTING STARTED -->
## Getting Started
To get a local copy just executed the following command:

```sh
git clone ${{env.REPOSITORY_GITHUB_URL}}
```

### Prerequisites
Nothing to do

### Installation
1. Install all the libraries

```sh
pip3 -m install -U -r requerements.txt
```

<!-- USAGE EXAMPLES -->
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
