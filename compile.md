# Installation

The rpm files can be created on amazon linux.
The debian files should better be created on a debian based system, like ubuntu.

## rpm packages

Amazon linux

`make rpm`

## Debian packages

### Additional packages on ubuntu

```bash
sudo apt-get update
sudo apt-get install devscripts build-essential lintian
sudo apt-get install  dh-virtualenv
apt-get install debhelper -t xenial-backports
```

### Setting locale for make rpm

```bash
sudo locale-gen de_DE.UTF-8
update-locale LANG=de_DE.UTF-8
```

### Create

`make deb`

