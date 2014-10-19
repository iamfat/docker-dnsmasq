docker-dnsmasq
==============

Bash script to add running docker containers to dnsmasq config and restart dnsmasq service.

```bash
sudo cp update-docker-dnsmasq /usr/local/bin
# DOCKERDNS_FILE=/etd/dnsmasq.d/docker 
# DOCKERDNS_SUFFIX=.docker.local
update-docker-dnsmasq
# DOCKERDNS_FILE will be generated
```
