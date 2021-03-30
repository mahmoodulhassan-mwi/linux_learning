in terminal $ mean normal user while # means super users
on terminal before $ or # is the present directory and before it is the machine name and before is user name
All the users (system service or custom) are in /etc/passwd
In /etc/passwd  file, the character after the user name is "x" and it means password is required to login as that user. Next is its ID and next is its group ID, then comment, then its home directory path and then user default shell.
passwords of all users are in /etc/shadow
groups are in file /etc/group
all the users home directories are in /home
In boot diretory we have boot loader (grub)  initrd.img-5.4.0-52-generic is the kernel file.
when we attach some media to our system, it is in media
/var is the directory where those file which are continuesly changing are placed. In /var/log is the important directory, as all the logs are in in this directory.
To view limited number of lines command is tail and with f flag you can view live log
To know all the files size present in directory use du -sh *
cd ..   cd -    
all the configurations of server, device is in /etc
to see all the mounted hard disk, USB, use command mount
in /dev directory we have all hardisl named as sda. so partition are named as /dev/sda1 /dev/sda2 similarly goes on
Second hard disk is named as sdb and its partitions are /dev/sdb1    /dev/sdb2    so on
3rd hard disk is sdd
4th hard disk is sdc
to see network state use command netstat  and with antp flags to see more details
gparted    shows partition of disk on GUI
