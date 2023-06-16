OpenWrt 22.03 arm_arm1176jzf-s_vfp repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_22.03/arm_arm1176jzf-s_vfp/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
