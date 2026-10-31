# PART L — NETWORK PROGRAMMING, AUTOMATION, AND MONITORING
### Theory questions
232. Explain the socket API and the roles of bind, listen, accept, connect, send, and receive.
233. Compare blocking and non-blocking I/O.
234. Explain concurrency options for a server: threads, processes, and asynchronous I/O.
235. Describe packet capture and the purpose of libpcap/tcpdump.
236. Explain SNMP polling versus traps/informs.
237. Describe metrics, logs, traces, and packet captures as observability signals.
238. Explain configuration management and idempotence.
239. Discuss safe handling of credentials, API tokens, and configuration secrets in automation.
240. Explain why monitoring thresholds require context and can produce false positives.

### Practical tasks
241. Write a TCP echo server and client with input validation, clean shutdown, and error handling.
242. Write a UDP time or status service and document its reliability limitations.
243. Write a Python script that checks a list of authorized lab hosts and reports reachability with timeouts.
244. Parse a sample network-device configuration file and report interface names, IP addresses, and enabled services.
245. Build a simple monitoring script that records latency and packet loss at fixed intervals during a short test.
246. Capture a short lab session with tcpdump and filter for DNS or ICMP traffic.
247. Create a dashboard or CSV report containing timestamp, host, status, latency, and error message.
248. Automate configuration backup for a lab device or server and verify that the backup can be restored.
