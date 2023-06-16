OpenWrt 22.03 mipsel_mips32 repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_22.03/mipsel_mips32/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
