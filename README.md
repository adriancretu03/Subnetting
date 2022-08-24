1) I allocated subnet 192.168.1.0/24 and I broke up this to support six subnets as follows
2) Three subnets with 6 hosts per subnet for sites 1, 2 and 3
3) Three subnets with 2 hosts per subnet for the links between routers and the Internet Router
4) For every site I configured the router with the last IP address, the switch with the second last IP address in the subnet 
and DHCP servers with the third last one, then I configured the DHCP server to allocate IP addresses to the clients for sites 1 and 2. 
5) For site 3 I manually configured hosts from first IP address
6) I also configured the DNS server for cisco.com and facebook.com, also the OSPF from the routers and the Internet Router.
7) Finally i verified that PCs could access cisco.com and facebook.com using their browsers
