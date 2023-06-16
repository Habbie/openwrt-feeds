OpenWrt 23.05 mips_4kec repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_23.05/mips_4kec/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
