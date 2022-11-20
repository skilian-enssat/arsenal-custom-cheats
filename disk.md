# disk

% Tools for disk images

#plateform/linux #target/local #cat/UTILS

## Info about disk image
found at https://unix.stackexchange.com/questions/316401/how-to-mount-a-disk-image-from-the-command-line
```
fdisk -lu <image>
```

## Mount disk image
found at https://unix.stackexchange.com/questions/316401/how-to-mount-a-disk-image-from-the-command-line
The offset is begin * sector size
```
sudo mount -o loop,offset=<offset> <image> <folder>
```

## Unount disk image
```
sudo umount <folder>
```