# How to Setup your Python Programming Environment on Linux, Ubuntu or Fedora.

### Ubuntu 14.04 and 16.04

If you are using Ubuntu 14.04 or 16.04, you can use Felix Krull's deadsnakes PPA at https://launchpad.net/~deadsnakes/+archive/ubuntu/ppa:
```sh
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.6
```
Alternatively, you can use J Fernyhough's PPA at https://launchpad.net/~jonathonf/+archive/ubuntu/python-3.6:

```sh
sudo add-apt-repository ppa:jonathonf/python-3.6
sudo apt-get update
sudo apt-get install python3.6
```

### Ubuntu 16.10 and 17.04

If you are using Ubuntu 16.10 or 17.04, then Python 3.6 is in the universe repository, so you can just run:
```sh
sudo apt-get update
sudo apt-get install python3.6
```
### Ubuntu 18.04
Python 3.65 is the default

### If you are on Fedora
```sh
sudo dnf install python36
```


