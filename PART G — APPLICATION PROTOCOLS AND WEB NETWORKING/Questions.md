# PART G — APPLICATION PROTOCOLS AND WEB NETWORKING
### Theory questions
131. Explain DNS resolution from a stub resolver through recursive and authoritative servers.
132. Compare DNS A, AAAA, CNAME, MX, NS, PTR, TXT, and SRV records.
133. Explain DHCP's address-allocation process and lease renewal.
134. Compare HTTP/1.1, HTTP/2, and HTTP/3 at a high level.
135. Explain HTTP methods, status codes, headers, cookies, sessions, and caching.
136. Describe TLS handshake basics and the role of certificates and certificate authorities.
137. Compare HTTP and HTTPS. What does TLS protect, and what does it not guarantee?
138. Compare SMTP, POP3, and IMAP.
139. Explain FTP, SFTP, and TFTP and their security differences.
140. Compare SSH and Telnet.
141. Explain SNMP, NTP, and their operational uses.
142. What are forward proxies and reverse proxies?
143. Explain load balancing and the difference between Layer 4 and Layer 7 balancing.
144. Describe WebSockets and how they support full-duplex communication.
145. Explain CDN edge caching and how it can reduce latency.

### Practical tasks
146. Use dig or nslookup to query A, AAAA, MX, NS, and TXT records for a domain you are authorized to inspect.
147. Use curl -I to inspect HTTP response headers from a public website and explain several fields.
148. Use Wireshark to identify a DNS query and response in a permitted capture; note that HTTPS payloads are normally encrypted.
149. Inspect your DHCP-assigned address, gateway, DNS servers, and lease details using your operating system's tools.
150. Run a local web server and test it with curl from the same machine and a second lab machine.
151. Configure SSH access between two lab machines using key-based authentication.
152. Set up a reverse proxy in a local lab and route requests to a backend web server.
153. Compare DNS lookup time and HTTP response time for a few test requests; state how you measured them.