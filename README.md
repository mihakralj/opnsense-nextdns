# opnsense-nextdns

This plugin depends on port package of nextdns that is available through a community repo.

1. Install community repo:

`fetch -o /usr/local/etc/pkg/repos/mimugmail.conf https://www.routerperformance.net/mimugmail.conf
pkg update`

2. install the NextDNS plugin:

`pkg add https://github.com/mihakralj/opnsense-nextdns/raw/main/os-nextdns-community-devel-0.3.txz`

3. remove the NextDNS plugin:

`pkg remove os-nextdns-community-devel`
