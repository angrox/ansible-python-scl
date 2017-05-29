# Python SCL

[![Build Status](https://travis-ci.org/angrox/ansible-python-scl.svg?branch=master)](https://travis-ci.org/angrox/ansible-python-scl)


This module has the following features:
* Installs/Enables Softwarecollections on CentOS and RHEL
* Installs a SCL python version
* Enables the python version globally


## Variables
scl_python_version: The version to use. Defaults to 35 (3.5.x). Possible values: 34 and 35

## Usage
Example playbook:
```
- hosts: all
  roles:
    - role: angrox.python-scl
```
