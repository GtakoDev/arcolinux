# Basic Aliases 
Arcolinux has multiple aliases that are made to be executed in a particular order.

1. buskel
The `bupskel` command is made to create a backup of the "/etc/spkel" directory before doing an update.
bubskel = 

2. update
This command will download and install all ArchLinux and Arcolinux packages. 
update = pacman -Syu

3. bupskel
The `bupskel` command is made to create a backup of the "/etc/spkel" directory after doing an update.


4. meld
uses the meld file comparing program to compare both backup folders of /etc/skel to see what changed

5. skel 
If everything is right, skel will copy all config files from /etc/skel to your home directory.

6. pksyua
This command updates remaining packages from the aur 

