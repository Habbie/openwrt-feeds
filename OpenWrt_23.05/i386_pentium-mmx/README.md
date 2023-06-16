OpenWrt 23.05 i386_pentium-mmx repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_23.05/i386_pentium-mmx/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
