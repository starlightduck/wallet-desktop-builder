# wallet-desktop builder
**Build scripts for wallet-desktop.**

Clone this repository and run the corresponding script.

## Linux

`build-wallet.sh` - for Linux, **run as root or with sudo**, tested on Ubuntu 20.04.3.

**Warning:** this script can mess with your default `gcc`, `g++` and `python` executables.

They will be set to `gcc-8`, `g++-8` and `python2.7` accordingly.

And in general it is a *very good idea* to review script before running it, especially as root.

The resulting wallet executable will be located in `Wallet` file, if everything goes good, ofcourse.