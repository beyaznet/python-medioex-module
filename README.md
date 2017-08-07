About
=====
Python [MedIOEx](https://github.com/pe2a/MedIOEx) extention module.

Table of contents
=================

- [About](#about)
- [Requirements](#requirements)
- [Installation](#installation)
    - [Installing the Raspbian packages](#installing-the-raspbian-packages)
    - [Installing bcm2835 C library](#installing-bcm2835-c-library)
    - [Installing Python MedIOEx module](#installing-python-medioex-module)

Requirements
============
- Python 3.x
- [bcm2835](http://www.airspayce.com/mikem/bcm2835/) C library

Installation
============
### Installing the Raspbian packages
```bash
apt-get install build-essential python3-dev python3-pip
```

### Installing bcm2835 C library
Download the latest version from [bcm2835](http://www.airspayce.com/mikem/bcm2835/)
```bash
tar zxvf bcm2835-1.xx.tar.gz
cd bcm2835-1.xx
./configure
make
make check
make installcheck
make install
```

### Installing Python MedIOEx module
```bash
pip3 install medioex
```
