<h1>Privilege Escalation:</h1><br>
If you found a command escalation vulnerability and now want to escalate your priviliges and if a executable has root permissions. You Can't read or execute the file then
try 




```
on the server
base64 -w 0 **scripthere**
copy it all up
on your machine
echo *paste* | base64 -d > script.sh
```




This will get you a hold of the script. You can further reverse the file.
