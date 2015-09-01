[![Build Status](https://travis-ci.org/RealSalmon/ansible-python-2.svg?branch=master)](https://travis-ci.org/RealSalmon/ansible-python-2)

RealSalmon.python-2
=======================
Ansible role to install Python 2.7, pip, virtualenv, and the python-dev package

Requirements
------------
- Ubuntu 14.04
- Ansible 1.9

Role Variables
--------------
- python_2_install_dev: true
- python_2_install_virtualenv: true
- python_2_install_pip: true

Dependencies
------------
None

Example Playbook
----------------
    ---
    - hosts: all
      roles:
        - RealSalmon.python-2

License
-------
BSD

Author Information
------------------
Ben Jones <ben@fogbutter.com>
