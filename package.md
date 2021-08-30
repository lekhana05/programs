# WHAT IS A PYTHON PACKAGE
#### A python package is a collection of modules. Modules that are related to each other are mainly put in the same package. When a module from an external package is required in a program, that package can be imported and its modules can be put to use.

#### Any Python file, whose name is the module’s name property without the .py extension, is a module.

#### A package is a directory of Python modules that contains an additional __init__.py file, which distinguishes a package from a directory that is supposed to contain multiple Python scripts. Packages can be nested to multiple depths if each corresponding directory contains its own __init__.py file.

![](pythok.png)


# INSTALLING  PACKAGES
#### There are two ways to install packages from PyPI. You can download the package and then run python setup.py install. But the modern way is to use pip, setuptools and wheel. Pip stands for Pip Installs Packages (yes, it's one of those acronyms) and is your front end for installation. If you have Python 2 >=2.7.9 or Python 3 >=3.4 installed from python.org, you will already have pip and setuptools, but will need to upgrade to the latest version: pip install -U pip setuptools or python -m pip install -U pip setuptools on Windows.
#### Use pip to install wheel: pip install wheel
#### Python packages are always installed into an environment. A common practice I will not cover here is to use virtual environments to manage multiple independent installations of Python with different interpreters and/or different sets of installed packages.