# cryptodev-python

The project creates Python bindings for [cryptodev](https://github.com/cryptodev-linux/cryptodev-linux/) which is 
written in C.\
The bindings are basically a Python module named cryptodev (under crypto).  
The module contains two Python files: ioctl.py and cryptodev.py translated from ioctl.h and cryptodev.h respectively.

To use the module import cryptodev into your python code. 
 ```python
from cryptodev import *
```  
You can find tests under /cryptodev-python/tests folder. These tests were originally written in C by the authors of 
[cryptodev](https://github.com/cryptodev-linux/cryptodev-linux/). 

## Installation 

Install [cryptodev](https://github.com/cryptodev-linux/cryptodev-linux/) module.
Cryptodev-python supports python 2.7 or higher and python 3.
Navigate to /cryptodev-python/tests folder and run run_tests.py:  
```
$ python run_tests.py
```
## Contributing


## Acknowledgment

I want to thank Vangelis Koukis for motivating me to develop this project.
