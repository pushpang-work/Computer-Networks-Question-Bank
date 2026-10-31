# Computer Networks: Beginner to Advanced Roadmap

This roadmap covers Computer Networks from fundamental concepts to advanced networking, network security, and practical administration.

## Phase 1: Networking Fundamentals — Beginner

- What is a computer network?
- History and evolution of computer networks
- Advantages, disadvantages, and applications
- Types of networks: PAN, LAN, MAN, WAN
- Network topologies: Bus, Star, Ring, Mesh, Tree, Hybrid
- Network architectures: Client-server and Peer-to-peer
- Network components: Hosts, servers, switches, routers, modems
- Transmission media: Wired and wireless
- Bandwidth, throughput, latency, jitter, and packet loss
- Circuit switching vs. packet switching
- Connection-oriented vs. connectionless communication

## Phase 2: Network Models and Protocols

- OSI reference model: All seven layers
- TCP/IP model and its layers
- OSI vs. TCP/IP model
- Encapsulation and decapsulation
- Protocol Data Units (PDU)
- Network interfaces and service access points
- Common network protocols
- Standards organizations: IEEE, IETF, ISO, ITU

## Phase 3: Physical Layer

- Analog and digital signals
- Signal encoding and modulation
- Bit rate and baud rate
- Transmission impairments and noise
- Serial vs. parallel transmission
- Synchronous vs. asynchronous transmission
- Simplex, half-duplex, and full-duplex communication
- Copper cables, fiber optics, and wireless transmission
- Multiplexing: FDM, TDM, WDM, CDM
- Switching technologies and transmission modes

## Phase 4: Data Link Layer

- Framing and frame synchronization
- Physical addressing and MAC addresses
- Error detection and correction
- Parity checks, checksum, CRC, Hamming code
- Flow control: Stop-and-Wait, Sliding Window
- ARQ protocols: Stop-and-Wait ARQ, Go-Back-N, Selective Repeat
- Medium Access Control (MAC)
- CSMA/CD and CSMA/CA
- Ethernet and IEEE 802.3
- Wireless LAN and IEEE 802.11 fundamentals
- VLANs and trunking
- Spanning Tree Protocol (STP)

## Phase 5: Network Layer

- Network-layer functions
- IPv4 addressing
- Binary, decimal, and hexadecimal conversions
- Classes of IPv4 addresses
- Public vs. private IP addresses
- Subnetting and supernetting
- CIDR and VLSM
- Network masks and prefix notation
- IPv6 addressing and transition mechanisms
- ARP and Neighbor Discovery
- ICMP and ICMPv6
- Packet fragmentation and MTU
- Routing fundamentals
- Static vs. dynamic routing
- Distance-vector and link-state routing
- Routing algorithms: Bellman-Ford and Dijkstra
- Routing protocols: RIP, OSPF, BGP
- NAT and PAT
- Multicast, broadcast, and unicast

## Phase 6: Transport Layer

- Process-to-process communication
- Port numbers and sockets
- TCP: Connection establishment and termination
- UDP and its applications
- TCP vs. UDP
- Three-way handshake
- Sequence and acknowledgment numbers
- Reliable data transfer
- Flow control and congestion control
- TCP sliding-window mechanism
- TCP retransmission and timeout
- Congestion-control algorithms
- Socket programming fundamentals

## Phase 7: Application Layer

- Domain Name System (DNS)
- HTTP and HTTPS
- FTP, SFTP, and TFTP
- SMTP, POP3, and IMAP
- DHCP
- Telnet and SSH
- SNMP
- NTP
- Proxy servers and reverse proxies
- Web servers and application servers
- Email delivery architecture
- REST APIs and network communication
- WebSockets and real-time communication

## Phase 8: Wireless and Mobile Networks

- Wireless communication fundamentals
- Wi-Fi architecture and security
- Bluetooth and Bluetooth Low Energy
- Cellular networks: 2G, 3G, 4G, 5G
- Mobile IP concepts
- Access points and wireless controllers
- Wireless roaming and handoff
- Ad hoc and mesh networks
- Satellite communication
- IoT networking protocols: MQTT, CoAP, Zigbee
- Wireless interference and channel planning

## Phase 9: Network Security

- Network security principles: CIA triad
- Threats, vulnerabilities, and attack surfaces
- Firewalls and firewall policies
- Stateful vs. stateless filtering
- IDS and IPS
- VPNs: IPsec and SSL/TLS VPNs
- Cryptography and public-key infrastructure
- TLS certificates and secure communication
- Authentication, authorization, and AAA
- RADIUS and TACACS+
- Network segmentation and access control lists
- DoS and DDoS attacks
- ARP spoofing, DNS spoofing, and packet sniffing
- Zero Trust networking
- Security monitoring and incident response

## Phase 10: Advanced Networking

- Advanced IPv4 and IPv6 routing
- BGP routing policies and route selection
- OSPF areas and route summarization
- MPLS and label switching
- Quality of Service (QoS)
- Traffic shaping and policing
- Load balancing and high availability
- Multicast routing
- Network convergence and redundancy
- Software-Defined Networking (SDN)
- Network Function Virtualization (NFV)
- Data center networking
- VXLAN and network overlays
- Anycast and content delivery networks
- IPv6 transition and tunneling mechanisms
- Network performance engineering

## Phase 11: Linux Networking and Administration

Especially useful if you want to administer Linux servers.

- Linux network interfaces and configuration
- IP addressing and routing tables
- `ip`, `ping`, `ss`, `ip neigh`, and `traceroute`
- DNS configuration and troubleshooting
- DHCP server and client configuration
- SSH server administration
- Linux bridges, VLANs, and bonding
- Firewall administration with `nftables` and `ufw`
- Packet filtering and forwarding
- NAT and IP forwarding
- Reverse proxies and load balancers
- Network namespaces and virtual interfaces
- Network services and port management
- Troubleshooting using system logs
- Server hardening and network monitoring

## Phase 12: Cloud, Virtualization, and Modern Networks

- Virtual networks and virtual switches
- VirtualBox and VMware networking modes
- NAT, bridged, host-only, and internal networks
- Docker networking and container communication
- Kubernetes networking fundamentals
- Cloud networking: AWS, Azure, and Google Cloud
- Virtual private clouds (VPCs)
- Cloud subnets, route tables, and gateways
- Site-to-site and client VPNs
- Infrastructure as Code for networking
- Network automation using Python
- Ansible for network configuration
- Network APIs and programmability
- Infrastructure monitoring and observability

## Phase 13: Practical Projects and Tools

1\. Network simulation

Build LANs, configure routers and switches, assign IP addresses, and test routing using Cisco Packet Tracer.

2\. Packet analysis

Use Wireshark to inspect DNS, TCP handshakes, HTTP, ICMP, and retransmissions.

3\. Linux network lab

Configure static IPs, routing, SSH, DNS, firewall rules, and a web server on your Ubuntu system.

4\. Advanced virtual lab

Use GNS3 or EVE-NG to simulate multi-router networks, routing protocols, and firewalls.


5\. Network programming

Build a TCP chat application, a UDP client-server program, a port checker, and a simple network monitor.

## Recommended learning order

| Level              | Topics to prioritize                                    |
| ------------------ | ------------------------------------------------------- |
| Beginner           | Fundamentals, OSI/TCP-IP, Ethernet                      |
| Intermediate       | IP addressing, subnetting, TCP/UDP, DNS, HTTP           |
| Upper intermediate | Routing, switching, VLANs, wireless, security           |
| Advanced           | Linux administration, VPNs, BGP, SDN, cloud networking  |
| Professional       | Troubleshooting, automation, monitoring, network design |
