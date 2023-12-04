# Mj's Reading Notes 

## Reading notes 6
NAT provides more security and provides more IP addresses for computers. 

1. What is the main purpose for implementing NAT on a network? for transmitting a private IP address to a public IP address or the other way around.
2. At what layer of the OSI model does NAT happen? it operates on the router and on layer 3 (network layer) of the OSI model.
3. What happens to packets when NAT runs out of addresses in the pool of available IPs? The packets will be dropped and an Internet Control Message Protocol (ICMP) host unreachable packet to the destination is sent.
4. What disadvantage does using NAT pose for routers? It should not tamper with port numbers but it has to because of NAT. Complicates tunneling protocols. Certain applications wont function while it is enabled. Translation results in switching path delays. 

I got my information from these sites
- [Network Address Translation (NAT)](https://www.geeksforgeeks.org/network-address-translation-nat/)
---
#### Videos
- [Network Address Translation (NAT)](https://www.professormesser.com/professor-messer-archives/n10-007/network-address-translation-3/)
- [Common Network Types](https://www.professormesser.com/professor-messer-archives/n10-007/common-network-types/)
- [IPv4 and IPv6 Addressing](https://www.professormesser.com/professor-messer-archives/n10-007/ipv4-and-ipv6-addressing/)

# Things I want to know more about