OpenWrt 21.02 mips_mips32 repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_21.02/mips_mips32/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
