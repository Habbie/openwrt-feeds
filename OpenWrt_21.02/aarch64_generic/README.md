OpenWrt 21.02 aarch64_generic repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_21.02/aarch64_generic/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
