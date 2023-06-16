OpenWrt 22.03 powerpc_8540 repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_22.03/powerpc_8540/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
