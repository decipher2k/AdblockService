# AdblockService
Adblocking Windows service based on Steven Black's hostsfile.<br>
This service runs a DNS proxy on localhost and filters out unwanted connections.<br>
The DNS traffic is redirected to Google's DNS Server and then filtered.<br>
Thus, it is way faster than webbrowser based adblockers.<br>
<br>
Please note:<br>
Some programs, like antivirus software or VPN's, do redirect DNS traffic.<br>
In this case, you will have to disable DNS redirection for those programs.<br>
Please note that this can lead to DNS leaks when using VPNs.<br>
<br>
Download:<br>
https://github.com/decipher2k/AdblockService/releases/tag/1.0
