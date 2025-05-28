# astro_setup
setup for experimental astrophysics work

Seteup is farily simple. You can load up the functions in to any jupyter notebook with:

```
%load_ext autoreload
%autoreload 2

import sys

#Load up the directory with the .py files for importing
sys.path.insert(0, "/home/kelcey/eelg_properties/python_files")


#Import the .py files you want
from func import *
```

Note the notebook and func.py file need to be at the same path level in your system.


I have a .ipnby file here which is a Jupyter Notebook that does all this super simply. Just check the paths to the files and make sure yours match.
