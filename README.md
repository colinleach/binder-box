# binder-box
Base boxes for MyBinder. This tiny repo creates a MyBinder environment then relies on nbgitpuller to connect this to the Jupyter notebooks at github.com/colinleach/astro-Jupyter. This allows frequent updates to the .ipynb files without needing (very slow) rebuilds of the binder environment.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/colinleach/binder-box/master/?urlpath=git-pull?repo=https://github.com/colinleach/astro-Jupyter)

Thanks to Tony Hirst ([psychemedia](https://github.com/ouseful-demos/binder-base-boxes)) for his advice on this.