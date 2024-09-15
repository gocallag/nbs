# nbs

nbs = network boot server

It is a set of cli scripts  and ansible playbooks that turns a almalinux 9 system into a server capable of PXE booting test systems in a lab environment.

Yes,  I use it in my lab environment, but i've tried / trying to make it as generic as possible.

dnf install -y epel-release
crb enable

dnf install -y ansible

./cli/initsys

edit /etc/nbs/vars/00root.yml and set config required