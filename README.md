# AdblockService
Adblocking Windows service based on Steven Black's hostsfile.<br>
This service runs a DNS proxy on localhost and filters out unwanted connections.<br>
The DNS traffic is being redirected to Google's DNS server and then filtered.<br>
Thus, it is way faster than webbrowser based adblockers. Useful if you can't afford a PiHole.<br>
<br>
Please note:<br>
Some programs, like antivirus software or VPN's, do redirect DNS traffic.<br>
In this case, you will have to disable DNS redirection for those programs.<br>
Please note that this can lead to DNS leaks when using VPNs.<br>
<br>
![grafik](https://user-images.githubusercontent.com/18600621/169657619-3a89de38-59e8-4c6a-a93b-189007eb58f3.png)
<br>

<br>
Download:<br>
https://github.com/decipher2k/AdblockService/releases/tag/1.0
