# nbs

nbs = network boot server

It is a set of cli scripts  and ansible playbooks that turns a centos 8 linux system into a server capable of PXE booting test systems in a lab environment.

Yes,  I use it in my lab environment, but i've tried / trying to make it as generic as possible.

Builds Tested
ESXi 6.7.0u3
ESXi 7.0.0
Centos 8.1

Please note:  You cannot use a syslinux package > 4.0.8,  the default syslinux in centos 8 wont boot ESXI 6.7 and above
