# GEF

% Commands for GDB GEF

#plateform/linux #target/local #cat/UTILS

## List functions
```
info functions
```

## List functions with a specific name
```
info functions <name>
```

## Run the program with arguments
```
run <args>
```

## Run the program with stdin from a file
```
run < <file>
```

## Run the program with stdin from python
```
run <<< $(python -c 'print "A"*100')
```

## Create pattern to find offset
```
pattern create <size>
```

## Find offset in pattern
```
pattern offset <address>
```

## Set the program file
```
file <program>
```

## Next instruction
```
ni
```

## Next instruction with a specific number of instructions
```
ni <number>
```

# Next intruction and step over function
```
si
```



## Display the stack
```
x/32x $esp
```

## Show content of memory
```
x/32x <address>
```

## Add a breakpoint
```
b <address>
```

## Add a breakpoint with a condition
```
b <address> if <condition>
```

## Add a breakpoint at a function
```
b <function>
```

