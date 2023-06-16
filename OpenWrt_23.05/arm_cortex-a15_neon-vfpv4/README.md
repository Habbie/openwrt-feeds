OpenWrt 23.05 arm_cortex-a15_neon-vfpv4 repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_23.05/arm_cortex-a15_neon-vfpv4/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
