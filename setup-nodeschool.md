# Nodeschool setup

## install Node

### install NVM: the Node Version Manager
this is the best tool to manage your Node setup as it allows you to change from one Node version to another very easily

#### on Linux
install [NVM](https://github.com/creationix/nvm) with this command:
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash
```
#### on Windows
use [nvm-windows](https://github.com/coreybutler/nvm-windows)

### install Node with NVM
NB: here, we don't install the latest version of Node as some worshops aren't compatible yet, but this will be easy to change in the future thank to NVM
```
nvm install 0.12
```
Close your terminal and reopen it: now `which node` should return something like `/home/myusername/.nvm/v0.12.7/bin/node`

If not:

* on Linux:

you might need to add a line to your bashrc (a file that is executed everytime you open a terminal) to reinitialize your node setup:
```
echo "nvm use 0.12" >> ~/.bashrc
```

## install the desired NodeSchool workshop

[pick a workshop](http://nodeschool.io/index.html#workshoppers) and follow the instructions there
