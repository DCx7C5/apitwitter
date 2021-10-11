# apitwitter
Malware_research

visualisation: https://www.maltego.com/downloads/


#### Bannergrabber using netcat (nc)
```bash
for x in {1..65535};do `printf "" | nc -vv -n -c -w1 104.245.32.240 $x`; done 
