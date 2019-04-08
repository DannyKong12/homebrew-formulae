# Python formula for 3.6.5_1

Latest homebrew does not allow you to downgrade from python 3.7, this formula will allow you to install python 3.6.5

# Installation:
If python3.7 is already installed, unlink it with

`brew unlink python`

Tap this repo

`brew tap DannyKong12/python`

Install

`brew install DannyKong12/python --ignore-dependencies`

Switch to the correct version of python

`brew switch python 3.6.5_1`

Verify the install was successful with

```
$ which python3
/usr/local/bin/python3
$ python3
Python 3.6.5
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Notes:
- this does not build the docs
- todo: figure out a way to install the correct version of sphinx-doc with a custom formula
