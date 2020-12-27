# ansible-docker-collection

## roles included:
- docker-netdata
- docker-csgo-server
- docker-netdataxyz
- docker-yt-dl

## reverse proxy:
When declaring the variable reverse_proxy_network, ports for supported web applications won't be directly exposed.

For example:
```
reverse_proxy_network: web
```
-> netdata would be reachable within the network "web".
