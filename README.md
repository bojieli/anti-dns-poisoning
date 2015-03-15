## DNS resolver to mitigate DNS poisoning

Requires VPN tunnel.

### Deployment Notes

* Requires bind 9.10+ to support rate limiting
* Need to create log directory "/var/log/named" with owner "bind" (the user who runs bind9 service).
