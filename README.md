# BinderTest

## Terminal approach

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akabla/BinderTest/HEAD)

Launch a terminal in Binder, and type:
```
python julia_install.py
python -i RHEOS.py
```
Rheos should now be available in python:
```
>>> RHEOS.Maxwell
<PyCall.jlwrap 
Model name: maxwell

Free parameters: η and k

                ___
            _____| |________╱╲  ╱╲  ╱╲  ___
                _|_|          ╲╱  ╲╱  ╲╱
                  η                  k
               >
```               

## Notebook install & run

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akabla/BinderTest/HEAD?filepath=InstallJulia.ipynb)
