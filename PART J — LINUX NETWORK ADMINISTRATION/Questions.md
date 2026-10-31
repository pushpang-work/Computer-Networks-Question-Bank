# PART J — LINUX NETWORK ADMINISTRATION

### Theory questions
192. Explain Linux network interfaces, interface states, and NetworkManager/systemd-networkd roles.
193. Describe the purpose of ip addr, ip link, ip route, ip neigh, ss, ping, traceroute, dig, and tcpdump.
194. Explain Linux routing, forwarding, bridges, bonding, and VLAN interfaces.
195. Compare ufw and nftables and describe where firewall rules fit into packet processing.
196. Explain IP forwarding, source NAT, destination NAT, and masquerading.
197. Describe network namespaces and their value for isolation and containers.
198. Explain DNS resolver configuration and common name-resolution failure modes.
199. Describe SSH hardening measures such as key authentication, restricted users, and limiting exposure.
200. Explain the difference between a service listening on 127.0.0.1, a specific interface address, and 0.0.0.0.
201. Describe a layered troubleshooting approach for a server that cannot reach the Internet.

### Practical tasks
202. On Ubuntu, record output from ip addr, ip route, ip neigh, ss -tulpen, and resolvectl status; explain the key fields.
203. Assign a static address to a disposable lab VM using the appropriate network manager and document how to roll back.
204. Configure a local SSH server and connect from another lab machine using SSH keys.
205. Host a test website on a Linux VM and restrict access with a firewall to the required ports.
206. Configure a Linux bridge or VLAN in a virtual lab and verify connectivity.
207. Create a network namespace and veth pair, assign addresses, and test connectivity between namespaces.
208. Configure a local DNS caching resolver in a lab and verify queries and cache behavior.
209. Write a Bash script that checks interface state, default route, DNS resolution, and connectivity, then prints a concise diagnostic report.
210. Troubleshoot a deliberately introduced lab fault such as a wrong gateway, DNS server, subnet mask, or firewall rule.
