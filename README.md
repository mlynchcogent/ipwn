Introduction
===
Here you will find some tools that I've created which may help you out on your next pentest. Nothing exciting as of yet, but useful. :)<br /><br>
Unfortunately, I wasn't able to capture screenshots of me using some of these tools in networks other than my home. However, I've tried to demonstrate how they're used via screenshots and videos as much as I can.

Tools
===
<br />
<b>iSMTP</b><br />
---------- <br />
There's been countless times when I've needed to test for SMTP user enumeration (RCPT TO and VRFY), internal spoofing, and relay. I've never found a tool that tested for all three and with great flexibility. iSMTP does just that, making it much easier to knock that process out of the way. <br />
	- Help menu: https://dl.dropboxusercontent.com/u/2526790/iSMTP/iSMTP.png <br />
	- Usage screenshot #1 (user enumeration): https://dl.dropboxusercontent.com/u/2526790/iSMTP/SMTP%20User%20Enumeration.png <br />
<br />
<b>iWebAudit</b><br />
---------- <br />
Many times, on an internal penetration test, you run across numerous web servers that you don't care about. As opposed to opening up every web server to see what they are, iWebAudit will scan a list of web servers and grab all their titles. By only reading a little bit from each server's response, this makes reporting only the titles much faster. <br />
	- Help menu: https://dl.dropboxusercontent.com/u/2526790/iWebAudit.png <br />
<br />
<b>pyFoca</b><br />
---------- <br />
If you're familiar with the Windows FOCA application, this is basically a python version of it. Pyfoca will use Google to discover files with extensions such as .pdf, .xls, .doc, etc. and download them. Once downloaded, it will extract all metadata which, in many cases, include usernames you can use for password attacks. <br />
	- Help menu: https://dl.dropboxusercontent.com/u/2526790/pyfoca.png <br />
<br />
<b>smbspider</b><br />
---------- <br />
Smbspider is a pretty smart when it comes to spidering Windows systems on internal networks. Once you get your hands on some credentials, you can pass them around with smbspider to try spidering systems that the user account has access to. In many cases, you'll end up quickly finding all types of sensitive data hanging out on employees' workstations. <br />
	- Help menu: https://dl.dropboxusercontent.com/u/2526790/smbspider/smbspider.png <br />
	- Usage screenshot #1: https://dl.dropboxusercontent.com/u/2526790/smbspider/smbspider%201.png <br />
	- Usage screenshot #2: https://dl.dropboxusercontent.com/u/2526790/smbspider/smbspider%202.png <br />
	- Usage video: http://www.youtube.com/watch?v=skVZwynHECw <br />
<br />
<b>smsspam</b><br />
---------- <br />
This was my first python script. I created this simple script when someone pissed me off by continuously playing on my phone. They quickly revealed their identity after approximately 50 text messages in about 10 seconds :).<br />
	- Help menu: https://dl.dropboxusercontent.com/u/2526790/smsspam.png <br />
<br />
<b>pymsf</b><br />
---------- <br />
My FUD meterpreter payload creator.<br />
	- Usage screenshot #1: https://dl.dropboxusercontent.com/u/2526790/pymsf.png <br />
<br />
<b>Nmap Parser</b><br />
---------- <br />
If you have tons of nmap results and want to look at them in a pretty table, check out this nmap result parser. <br />
	- Usage screenshot #1: https://dl.dropboxusercontent.com/u/2526790/nmap_parser.png <br />
	- Usage screenshot #2: https://dl.dropboxusercontent.com/u/2526790/nmap_parser1.png <br />

Credits:
===
Josh Stone - inspiration for writing smbspider <br />
Victor Mata - inspiration for writing iWebAudit
