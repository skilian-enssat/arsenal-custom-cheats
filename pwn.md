# pwn

% Tools to exploit binaries and binary exploitation

#plateform/linux #target/local #cat/UTILS

## Check the securities of a linux ELF binary
```
checksec <file>
```

## Check the protections of a windows binary
```
$A_SCRIPTS/gdb/winchecksec <file>
```

## Find gadgets in a windows binary
```
$A_SCRIPTS/gdb/rp-lin-x64 -f <file> -r 2
```

## Create an exploit template
```
pwn template > exploit.py
```