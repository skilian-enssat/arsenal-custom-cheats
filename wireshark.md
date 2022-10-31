# wireshark

% extract connexions from pcap or cap files

#plateform/linux #target/local #cat/UTILS

## Follow tcp stream and messages from capture file
using tshark
```
tshark -q -r <capture-file> -z follow,tcp,ascii,0
```

## Extract trafic from iodine DNS tunnel
script from https://blog.nlegall.fr/ecw-data-exfiltration.html
Will be extracted as extracted.pcap
```
python2 $A_SCRIPTS/iodine/exploit.py <capture-file> <domain>
```