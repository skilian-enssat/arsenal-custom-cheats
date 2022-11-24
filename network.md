# network

% configure networking

#plateform/linux #target/local #cat/UTILS

## Show information about ip addresses and interfaces
comment not displayed nor used to search
```
ip addr
```

## Add an ip to an interface 
```
ip addr add <ip-addr>/<mask> dev <interface>
```

## Remove/Delete an ip from an interface
```
ip addr del <ip-addr>/<mask> dev <interface>
```

## Change the status of an interface
```
ip link set <interface> <up-or-down>
```

## Remove/Delete all ip addresses from an interface
```
ip addr flush dev <interface>
```

## Show information about routes
```
ip route
```

## Add a route via a gateway
```
ip route add <ip-addr>/<mask> via <gateway-ip>
```

## Add a route via/through a specific interface
```
ip route add <ip-addr>/<mask> dev <interface>
```

## Remove/Delete a route
```
ip route del <ip-addr>/<mask> via <gateway-ip>
```

## Remove/Delete a route via/through a specific interface
```
ip route del <ip-addr>/<mask> dev <interface>
```

## Change/Modify/Update a route
```
ip route change <ip-addr>/<mask> via <gateway-ip> dev <interface> metric <posterity>
```

## Simulate a route take to a destination
```
ip route get <ip-addr>
```

