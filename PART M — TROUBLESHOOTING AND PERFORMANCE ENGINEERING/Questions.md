# PART M — TROUBLESHOOTING AND PERFORMANCE ENGINEERING

### Theory questions
249. Explain a structured troubleshooting method from physical layer to application layer.
250. Differentiate symptoms, root causes, contributing factors, and corrective actions.
251. How do latency, jitter, loss, and bandwidth affect interactive and bulk applications differently?
252. Explain why ping success does not prove that a specific application service is working.
253. Describe common causes of DNS, DHCP, routing, MTU, duplex, and certificate failures.
254. Explain packet retransmissions, duplicate acknowledgements, and out-of-order delivery.
255. Describe baseline measurements and why repeatable tests matter.
256. Explain how to distinguish server overload from network congestion using evidence.
257. Discuss the limits of traceroute and ICMP-based diagnostics.

### Practical tasks
258. Use a fault-isolation worksheet to diagnose a host that can reach its gateway but not resolve domain names.
259. Investigate a simulated case where a website resolves correctly but the TCP connection fails.
260. Use Wireshark to identify a TCP retransmission or DNS failure in a supplied or self-generated lab capture.
261. Compare throughput at different times and record test conditions, including link type and competing traffic.
262. Create a decision tree for diagnosing 'Internet not working' reports.
263. Write a post-incident report with timeline, impact, evidence, root cause, remediation, and prevention.
