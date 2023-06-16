OpenWrt 22.03 x86_64 repository for dnsdist
========

Binaries built from this repository on 2023-06-16 can be downloaded from <https://PowerDNS.github.io/pdns/>.

To install the dnsdist package, run

```
echo "src/gz pdns https://PowerDNS.github.io/pdns/OpenWrt_22.03/x86_64/base" >> /etc/opkg/customfeeds.conf
opkg update
opkg install dnsdist
```
