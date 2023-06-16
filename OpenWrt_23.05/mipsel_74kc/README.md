OpenWrt 23.05 mipsel_74kc repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_23.05/mipsel_74kc/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
