# Proteus Nu Wallet .deb Debian Package

Installation instructions 64-bit -

GDEBI -

Gdebi is a .deb installation file common in Debian but also found on Ubuntu.

$ sudo apt-get install gdebi
$ cd ~/
$ wget 'https://github.com/proteanx/nunetwork/raw/master/deb/nubits_5.0-1.deb'
$ sudo gdebi nubits_5.0-1.deb

Now finish install via Gdebi GUI

--- Optional (Remove deb package) ---

$ cd ~/
$ sudo rm nubits_5.0-1.deb

Command Terminal via dpkg

$ cd ~/
$ wget 'https://github.com/proteanx/nunetwork/raw/master/deb/nubits_5.0-1.deb'
$ sudo dpkg -i nubits_5.0-1.deb
$ sudo apt-get install -f

--- Optional (Remove deb package) ---

$ cd ~/
$ sudo rm nubits_5.0-1.deb
