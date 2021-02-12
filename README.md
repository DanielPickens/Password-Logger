# Password-Logger
My version of the password logger program



TOOL CAN:

It specifically sniffs for cookie and form passwords data from open wifi in monitor mode
one-click to launch a browser with sniffed brownie.

This tool does not require ARP attack, just silent sniffing, thus invisible to victim. Besides, the sniffing does not require one to associate AP, making it even more diffcult to detect.

#Requirements:

PyQT >=4
Scapy >=2.0
* Backtrack5 

#Usage:

e.g: python fudgebrownie.py -i en0 [-c 1]

File / Interface
    -i --interface <interface>    Choose specified interface
    -f --file <filename>         Choose specified filename
    -c --channel <channel>      Choose specified channel (For Mac OS X only)
On poping cookie window, right click on useragent items and select "launch attack" to open a browser using sniffed cookie. Sniffed passwords are stored in bigCookie.log

