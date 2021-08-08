# scratchhh
[![img](https://shields.io/badge/view-on%20github-black?logo=github)](https://github.com/themysticsavages/scratchhh)
[![img](https://shields.io/badge/pypi-0.1.2\-blue?logo=pypi)](https://pypi.org/package/scratchhh)
[![scratch](https://scratch.mit.edu/images/logo_sm.png)](https://scratch.mit.edu)

scratchhh is a kinda thin wrapper for the Scratch API. It makes things easier to fetch and use.

## Installation
With pip:
```
python -m pip install scratchhh
```
Or manually:
```
python setup.py install
```

## Usage
### getUserProj
```py
# Get projects from a specific user
from scratchhh.scratchhh import Scratch
Scratch.getUserProj(user, num)
```
### getThumb
```py
# Get a project thumbnail
from scratchhh.scratchhh import Scratch
Scratch.getThumb(id, file)
```
### searchProj
```py
# Search for projects
from scratchhh.scratchhh import Scratch
Scratch.searchProj(query, num)
```
### getInfo
```py
# Get project information
from scratchhh.scratchhh import Scratch
Scratch.getInfo(id)
```
### getUserAv
```py
# Get a user avatar
from scratchhh.scratchhh import Scratch
Scratch.getUserAv(user, file)
```

More features will be added as project development moves!