Network
===

main.jeffmccune.net maps to main.lan

External Network
===

Minimal SSH
---

```
Host main
  Hostname main.jeffmccune.net
  Port 22001
  User root
```

```
Host home
  Hostname home.jeffmccune.net
  Port 22042
  User localadm
```

Namecheap Dynamic DNS
---

Dynamic DNS:

jeffmccune.net is hosted on Namecheap DNS.  The NS record is:

```
# dig ns jeffmccune.net
;; ANSWER SECTION:
jeffmccune.net.		1800	IN	NS	freedns3.registrar-servers.com.
jeffmccune.net.		1800	IN	NS	freedns2.registrar-servers.com.
jeffmccune.net.		1800	IN	NS	freedns5.registrar-servers.com.
jeffmccune.net.		1800	IN	NS	freedns1.registrar-servers.com.
jeffmccune.net.		1800	IN	NS	freedns4.registrar-servers.com.
```

home.jeffmccune.net
---

The original network, running off-site at a friends house.  Currently connected
to Fiber sphere with substantial bandwidth.

main.jeffmccune.net
---

The network at Main St.  Currently connected to Comcast internet with 50 Mbit
download, 5Mbit upload.

Firewall is running pfSense in a VM.

Notable Hosts
===

 * http://pfsense.main.lan
 * http://gw.home.lan
