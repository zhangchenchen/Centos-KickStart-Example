# Centos-KickStart-Example
a kickstart file for installing Centos/RH automately


# What we do

wo do some moves as follow:

- In command section, do some common operation, set language & keyboard, password and so on. 
- In pre section, we detect hard drives for installing operation system and make partition, you can custom as your own. 
- In post section, we make a local yum repo, add some service start on boot, configure salt, etc. Also, do as your demand.
- In packages section, install some necessary packages.