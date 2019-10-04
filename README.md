# cats-dnsmasq
DNS server for nuage deployment:
# workflow
* Change FQDNs and IPs in `dnsmasq.conf`
* Change FQDNs and IPs in `xmpp.hosts` for xmpp records
* Run it: `docker-compose up -d`
* Your DNS server will be avilible at docker-host ip
