sudo useradd -m zohartheboss
sudo passwd zohartheboss

mkdir code
mkdir test
mkdir personal 
mkdir misc

A- cd /home/Zohartheboss/test
B- cd ./test
C- echo "hello A" > ./misc/fileA
D- touch fileB then i used echo "content" > fileB to populate file B
E- cp fileA fileC
F- mv fileB fileD
G- tar -cvf misc.tar misc
H- tar -czvf misc.tar.gz misc
I- chage -d 0 newuser
J- sudo passwd -l newuser
K- useradd -s /sbin/nologin username
L- sudo vi /etc/ssh/sshd_config change passwordauthentication no
M- PermitRootLogin no