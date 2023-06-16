OpenWrt 22.03 mipsel_24kc_24kf repository for dnsdist
========

To install the dnsdist package, run

```
echo "src/gz pdns /OpenWrt_22.03/mipsel_24kc_24kf/dnsdist" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
