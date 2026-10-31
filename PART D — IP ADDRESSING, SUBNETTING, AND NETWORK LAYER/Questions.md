# PART D — IP ADDRESSING, SUBNETTING, AND NETWORK LAYER

### Theory questions
59. Explain the main responsibilities of the network layer.
60. Convert binary numbers to decimal and decimal numbers to binary; show the place values.
61. Explain IPv4 address structure, network bits, host bits, and subnet masks.
62. Compare classful addressing with classless addressing (CIDR).
63. Explain public, private, loopback, link-local, multicast, and limited-broadcast IPv4 ranges.
64. What is CIDR notation? Interpret /24, /26, /20, and /30.
65. Explain subnetting, supernetting, and VLSM and why they are useful.
66. Describe IPv6 address notation, prefix length, compression, and address types.
67. Compare IPv4 and IPv6, including address size, broadcast behavior, and neighbor discovery.
68. Explain ARP, ICMP, ICMPv6, and IPv6 Neighbor Discovery.
69. What are MTU and fragmentation? Explain the impact of an MTU mismatch.
70. Explain NAT and PAT. What benefits and limitations do they have?
71. Compare unicast, multicast, and broadcast at the network layer.
72. Explain the purpose of a default gateway and routing table.
73. Describe packet forwarding from one subnet to another.

### Numerical and subnetting problems
74. A host has IP address 192.168.10.77/24. Find the network address, broadcast address, and usable host range.
75. Divide 192.168.1.0/24 into four equal subnets. Give each subnet's network, usable range, broadcast, and prefix.
76. Design subnets for departments requiring 100, 50, 25, and 10 hosts using VLSM from 10.10.0.0/23. Show allocation order and unused space.
77. How many total addresses and conventional usable host addresses are in a /27 IPv4 subnet? Mention relevant special cases.
78. Determine whether 172.16.8.130/26 and 172.16.8.190/26 are in the same subnet. Show the calculation.
79. Summarize 192.168.0.0/24 through 192.168.3.0/24 into the smallest valid aggregate route, if possible.
80. Convert 11000000.10101000.00000001.10000000 to dotted-decimal IPv4 notation.
81. An IPv6 address is 2001:0db8:0000:0000:0000:ff00:0042:8329. Compress it according to IPv6 notation rules.
82. A network requires 500 hosts. What is the smallest conventional IPv4 prefix that supports this requirement? Show your reasoning.

### Practical tasks
83. Use ip addr (Linux) or ipconfig (Windows) to inspect your IP address, prefix/subnet mask, and interface state.
84. Use ip route or route print to inspect the routing table; identify the default route.
85. Use ip neigh or arp -a to inspect neighbor-cache entries before and after pinging a local host.
86. Create a subnetting worksheet for at least six networks with different host requirements.
87. Configure static IPv4 addresses on two hosts in a lab and verify same-subnet communication.
88. Configure two subnets and a router in a simulator; verify that traffic crosses the router.
89. Use ping with different packet sizes where supported to investigate MTU-related behavior safely on your own network.
90. Document the IPv6 addresses on your device and distinguish link-local from global/unique-local addresses where present.