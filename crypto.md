# crypto

% Tools for cryptography

#plateform/linux #target/local #cat/UTILS

## Uncipher file with RSA CTF tool
foud at https://github.com/RsaCtfTool/RsaCtfTool
```
python3 RsaCtfTool.py --publickey *.pem --uncipherfile <file> --private
```

## Find private RSA key from public key with RSA CTF tool
```
python $SCRIPTS_PATH/RsaCtfTool/RsaCtfTool.py --publickey *.pem --private
```

## Dump the parameters from a RSA key with RSA CTF tool
```
python $SCRIPTS_PATH/RsaCtfTool/RsaCtfTool.py --dumpkey --key <key>
```
