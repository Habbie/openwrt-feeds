OpenWrt 22.03 i386_pentium-mmx repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_22.03/i386_pentium-mmx/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
