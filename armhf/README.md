# Proteus nud armhf binary built on Raspbian via Raspberry Pi 2 B+ 

Installation instructions -

$ sudo apt-get install libssl-dev libdb++-dev libminiupnpc-dev
$ sudo apt-get install libboost-dev libboost-system-dev libboost-filesystem-dev libboost-program-options-dev libboost-thread-dev libcurl4-openssl-dev
$ cd ~/
$ wget 'https://github.com/proteanx/nunetwork/raw/master/armhf/nud'
$ sudo mv nud /usr/bin/
$ sudo chmod a+x /usr/bin/nud

Make sure you have your nu.conf 

$ mkdir .nu
$ sudo nano .nu/nu.conf

Fill in nu.conf info

$ sudo chmod 600 nu.conf

Now run nud and begin downloading the blockchain

$ nud -daemon

wait a few minutes

$ nud getinfo




