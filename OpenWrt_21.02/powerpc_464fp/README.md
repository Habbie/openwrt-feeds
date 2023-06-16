OpenWrt 21.02 powerpc_464fp repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_21.02/powerpc_464fp/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
