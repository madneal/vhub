# CH4INRULZ

## Introcution 

target: 192.168.3.154
kali: 192.168.3.153
purpose: To the root of the target machine

## Information Enumeration

Firstly, detect the open ports of target machine:

```
nmap -sT -p- -oA openports 192.168.3.154
```

[![AArFDP.png](https://s2.ax1x.com/2019/03/14/AArFDP.png)](https://imgchr.com/i/AArFDP)

Then detect the detailed services:

![AArEE8.png](https://s2.ax1x.com/2019/03/14/AArEE8.png)

So we can see that the port of `21, 22, 80, 8011`. And from the detailed services detection, we can have a comprehensive knowing of the target machine.

## Exploitation

### ftp

try to login with ftp, as it allowed anonymous login. But nothing found.

