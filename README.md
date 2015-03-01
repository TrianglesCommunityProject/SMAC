Copyright (c) 2015 SMAC Developers
SMAC development tree
SMAC is a PoW/PoS-based cryptocurrency designed as the currency for the Social Media Advertisement Industry.

http://smac.io


###Building Instructions
####Ubuntu (tested 14.X x64)
````
apt-get install -y ntp git build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev libqrencode-dev libcurl4-openssl-dev automake make
````
````
For smaller RAM systems, you may need to create a swap file for systems to build.
This usually happens with under 1GB RAM
UBUNTU:
````
sudo dd if=/dev/zero of=/swapfile bs=64M count=16
sudo mkswap /swapfile
sudo swapon /swapfile
````

Development process
===========================
Changes are submitted through pull requests. All changes for minor updates will be accepted through pull requests.
Changes to the core requiring any forks will be proven tested using the testnet block chain with impacted code. Non
urgent forks will take place in a two week time frame (20160 blocks) from announcements to allow clients to update and
network to remain stable.
