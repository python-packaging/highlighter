# highlighter

Easy to use PEP 508 markers.

```py
from packaging.markers import Marker
from highlighter import EnvironmentMarkers

env = EnvironmentMarkers.for_python("3.7.5", "win32")
m = Marker("python_version < '3.7'")
print("Match?", env.match(m))
```

# License

highlighter is copyright [Tim Hatch](https://timhatch.com/), and licensed under
the MIT license.  I am providing code in this repository to you under an open
source license.  This is my personal repository; the license you receive to
my code is from me and not from my employer. See the `LICENSE` file for details.
