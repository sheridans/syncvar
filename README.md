# syncvar

Useful utilizing rsync to sync files from physical disk to memory disk on system start up. Can also be used on system shutdown to mount read only physical disks and sync the contents back from RAM before shutdown. 

Because it uses rsync, very easy to use and exclude unwanted directories such as /tmp etc.
