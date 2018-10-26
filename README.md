# OpenBSD Wireless Network Manager

Usage :
	$ doas ./wifi-menu <interface\>
```
  .;'  ,;'             `;,  `;,    OpenBSD wireless network manager
 .;'  ,;'  ,;'     `;,  `;,  `;,
 ::   ::   :   ( )   :   ::   ::
 ':.  ':.  ':. /_\ ,:'  ,:'  ,:'
  ':.  ':.    /___\    ,:'  ,:'
   ':.       /_____\      ,:'
            /       \ 

1) Normal.iwn0         2) Test.iwn0             7) Raspi3.iwn0
2) Privacy.iwn0        3) Android.iwn0
3) MyVPN.iwn0          4) CryptoLab.iwn0

[+] Choose a previously saved wifi connection or "Enter" to skip:
1) Android1        4) Wifi4          7) Wifi7
2) Wifi2           5) Wifi5
3) Wifi3           6) Wifi6

[+] Choose wifi connection or "Enter" to quit: 1
[+] Enter the passphrase for "Android1"?
[+] Password:
[+] Creating new configuration using "Android1"
[+] Connecting using file "Android1"
[+] Configured interface iwn0; ESSID is "Android1"
[+] Interface iwn0 is up
[+] Running dhclient
iwn0: no lease..... got lease
iwn0: bound to 192.168.43.113 from 192.168.43.1 (12:34:56:78:9a:bc)
dnscrypt_proxy(ok)
dnscrypt_proxy(ok)
unbound(ok)
unbound(ok)
```
