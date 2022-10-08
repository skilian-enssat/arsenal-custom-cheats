# hydraPLUS

% hydraPLUS

#plateform/linux

## Bruteforce username in login form
```
hydra -L <worldlist> -p test <ip> http-post-form "<path>:<request>:<denied_message>"
```

## Bruteforce password in form
```
hydra -l <login> -P <wordlist> <ip> http-post-form "<path>:<request>:<denied_message>"
```

## Bruteforce username and password in login form
```
hydra -L <wordlist_login> -P <wordlist> <ip> http-post-form "<path>:<request>:<denied_message>"
```