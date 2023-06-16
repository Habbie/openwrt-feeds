OpenWrt 22.03 aarch64_cortex-a53 repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_22.03/aarch64_cortex-a53/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
