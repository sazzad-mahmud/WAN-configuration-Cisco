# WAN-configuration-Cisco
#I've done this in packet tracer version 3.7.1

Scenario: 

1.	Configure for Head Office and Branch Office
2.	Each branch will have 2 ISP data connectivity for link redundancy 
3.	Branch network have a number of VLANs (Data, CCTV, SWIFT)
4.	DHCP enabled in switch for different VLANs
5.	Manager at Data VLAN will have access to CCTV network
6.	SWIFT will not be accessible from any other VLANs of Branch network
7.	Establish GRE tunnel between Head Office and Branch network 
8.	Static Routinh
9.	Inter VLAN routing and ACL at router
10.	Switch will have ip address configured for each VLAN
11.	Sub-interface need to create at router for each VLAN
12.	Minimum 2 PC at Data VLAN, 1 PC at CCTV and 1 PC at SWIFT VLAN 
