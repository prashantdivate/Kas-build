# Kas-build system for Yocto build

## Install Pre-requisite
```
$ sudo apt-get install python3.6
$ pip3 install kas
```
## Create virtual environment in python
```
$ python3 -m venv kasdemo
$ source kasdemo/bin/activate
```
## Setup Kas configurations in yml file
```
$ vim kas-main.yml
```
## Initiate the Kas build process
```
$ kas build kas-main.yml
```
