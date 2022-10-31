# hexdump

% Display hexadecimal dump of a file

#plateform/linux #target/local #cat/UTILS

## Dump bytes in hexadecimal with address
```
hexdump <file>
```

## Dump bytes in hexadecimal with address and ASCII representation
```
hexdump -C <file>
```

## Dump bytes in hexadecimal with address and ASCII representation, with offset
```
hexdump -C -s <offset> <file>
```

## Dump bytes in hexadecimal without address
```
xxd -p <file>
```