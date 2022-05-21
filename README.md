# AdblockService
Adblocking Windows service based on Steven Black's hostsfile
This service runs a DNS proxy on localhost and filters out unwanted connections.
The DNS traffic is redirected to Google's DNS Server and then filtered.
Thus, it is way faster than webbrowser based adblockers.

Please note:
Some programs, like antivirus software or VPN's, do redirect DNS traffic.
In this case, you will have to disable DNS redirection for those programs.
Please note that this can lead to DNS leaks when using VPNs.

Download:
https://github.com/decipher2k/AdblockService/releases/tag/1.0
