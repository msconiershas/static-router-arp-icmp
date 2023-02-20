# static-router-arp-icmp

Static Router - Programming Assignment #2
Building a static router using the switchyard framework with the following functionalities:

Respond to ARP (address resolution protocol) requests for addresses that are assigned to interfaces on the router.
Make ARP requests for IP addresses that have no known Ethernet MAC address.
Receive and forward packets that arrive on links and are destined to other hosts.
Respond to ICMP messages like echo requests ("pings").
Generate ICMP error messages when necessary, such as when an IP packet's TTL (time to live) value has been decremented to zero.
