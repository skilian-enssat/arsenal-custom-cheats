# ldap

% ldap servers interactions

#plateform/linux #target/remote #cat/RECON

## null bind without DN domain
```
ldapsearch -H ldap://<ip>:<port> -x -s base '' "(objectClass=*)" "*" +
```

## null bind with DN domain
```
ldapsearch -H ldap://<ip>:<port> -x -b <DN>
```