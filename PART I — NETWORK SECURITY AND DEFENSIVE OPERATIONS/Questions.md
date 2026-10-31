# PART I — NETWORK SECURITY AND DEFENSIVE OPERATIONS

### Theory questions
169. Explain the confidentiality, integrity, and availability (CIA) triad.
170. Differentiate threat, vulnerability, exploit, risk, and control.
171. Compare packet-filtering, stateful, and application firewalls.
172. Explain IDS versus IPS and signature-based versus anomaly-based detection.
173. Describe authentication, authorization, accounting (AAA), RADIUS, and TACACS+.
174. Explain symmetric encryption, public-key cryptography, hashing, and digital signatures.
175. Describe TLS certificates, certificate chains, expiry, and hostname validation.
176. Compare site-to-site VPNs and remote-access VPNs; explain IPsec and TLS VPNs.
177. Explain network segmentation, ACLs, least privilege, and Zero Trust.
178. Describe ARP spoofing, DNS spoofing, rogue access points, and packet sniffing at a conceptual level.
179. Explain denial-of-service and distributed denial-of-service attacks and common defensive controls.
180. Describe secure network logging, time synchronization, alerting, and incident response.
181. Explain why encryption does not automatically protect against compromised endpoints or malicious insiders.
182. Discuss the principle of defense in depth.

### Practical tasks — authorized lab only
183. Create a host firewall policy that allows only required services on your own lab machine; verify allowed and denied connections.
184. Use Wireshark to inspect a provided or self-generated capture for DNS, TCP, TLS, and ICMP metadata without attempting to decrypt unauthorized traffic.
185. Generate a self-signed certificate for a local test service and explain browser trust warnings and certificate validation.
186. Configure a VPN between lab systems or use a simulator; document routing and access boundaries.
187. Write a least-privilege firewall rule plan for a web server, database server, and administrator workstation.
188. Review authentication and system logs on your own Linux server and identify successful and failed login events.
189. Create a simple incident-response checklist for a suspected compromised workstation.
190. Run a security review of your own lab configuration: exposed ports, unnecessary services, patch status, firewall rules, and SSH settings.
191. Use a deliberately vulnerable training environment only if isolated and authorized; document findings and mitigations rather than targeting public systems.