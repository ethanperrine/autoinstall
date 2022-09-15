# autoinstall
Automatically installs Python Libraries for your clients.

# Credits to Desmond for making Pipper
gh: D35m0nd142/Pipper

His was in python 2.7, i just updated his code to be compatable with the latest python version to date. 

# How to use?
copy the autoinstall.py to your project file and import it as it follows. 

```
from autoinstall import pip_install_module

try:
  import module_name
except:
  pip_install_module("module_name")
  
```

credits to original creator:
https://github.com/D35m0nd142/Pipper
