OpenWrt 23.05 x86_64 repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_23.05/x86_64/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
