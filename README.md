# Premium AutoScript

Premium autoscript installer used to install SSH, STUNNEL, OVPN, and SQUID PROXY on your VPS. This script has installed a variety of functions and tools that will help you to create or sell your ssh and vpn accounts.

### Update:
-IPTables has been removed; causing interference with internet connectivity, making all connection cannot be established.

-Fix menu not shown in terminal. Perma-link has been fixed and added into the script. 

-Added zip installation on the script.

-With all due respect, all source credit to DopeKidVPN. I just re-modified certain things to make things available to install and use on-the-go.

### Installation:


- Debian 9 x64 & x32

apt-get -y install wget && wget https://raw.githubusercontent.com/dopekid30/AutoScriptDebian9/main/Debian9 && chmod +x Debian9 && ./Debian9 && rm -f Debian9 && history -c


### Important Information:

- Fail2Ban

- Ddos Deflate

- IP Tables

- Webmin - http://VPSIP:10000/

- Simple Panel - http://VPSIP:85/

- Openvpn Monitor - http://VPSIP:89/

- OVPN Config - http://VPSIP:85/Dopekid.ovpn | http://VPSIP:85/DopekidVPN.tar.gz or http://VPSIP:85/Dopekid.tar.gz


### Service and Port Informations:

- OpenVPN : TCP 443

- OpenSSH : 22, 90 & 143

- Stunnel/4 : 444

- Dropbear : 80, 109, 110 & 442

- Squid Proxy : 3128, 8000, 8080 & 8888

- Badvpn : 7300

- Nginx : 85


### Server Tools:

- htop

- iftop

- mtr

- nethogs

- screenfetch


### Script By:

https://www.facebook.com/joash.singh.90
