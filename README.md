# SynologyDDNS
Synology cloudflare ddns only ipv6

if open open vSwitch, default eth0
`ip6fetch=$(ip -6 addr show ovs_eth0 | grep -oP "$ipv6Regex")`

Modify from https://github.com/joshuaavalon/SynologyCloudflareDDNS
            https://github.com/joshuaavalon/SynologyCloudflareDDNS/pull/18
