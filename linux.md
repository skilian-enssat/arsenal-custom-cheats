# linux

% linux commands

#plateform/linux #target/local #cat/UTILS

## Chown on a directory recusively
```
chown -R <user>:<group> <directory>
```

## Find executables with the setuid bit set
```
find <dir> -perm -u=s -type f 2>/dev/null
```

## List disks
```
lsblk -S
```

## List partitions
```
lsblk
```

## unmount a partition with umount
```
umount <partition>
```

## Flash an iso image to a disk
Be careful, this will erase the disk
```
dd if=<iso-image> of=<disk> bs=4M status=progress conv=fdatasync
```