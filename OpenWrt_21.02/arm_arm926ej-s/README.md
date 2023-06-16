OpenWrt 21.02 arm_arm926ej-s repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_21.02/arm_arm926ej-s/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
