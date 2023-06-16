OpenWrt 23.05 aarch64_generic repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_23.05/aarch64_generic/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
