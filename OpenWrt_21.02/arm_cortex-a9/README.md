OpenWrt 21.02 arm_cortex-a9 repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_21.02/arm_cortex-a9/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
