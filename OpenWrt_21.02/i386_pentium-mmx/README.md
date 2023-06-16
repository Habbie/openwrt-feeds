OpenWrt 21.02 i386_pentium-mmx repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_21.02/i386_pentium-mmx/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
