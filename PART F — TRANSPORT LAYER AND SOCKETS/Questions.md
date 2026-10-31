# PART F — TRANSPORT LAYER AND SOCKETS
### Theory questions
112. Explain process-to-process delivery and the role of port numbers.
113. Compare TCP and UDP, including reliability, ordering, overhead, and common use cases.
114. Explain TCP's three-way handshake and connection termination.
115. Describe TCP sequence numbers, acknowledgements, retransmissions, and timeouts.
116. Explain TCP flow control and the receiver-advertised window.
117. Explain congestion control and distinguish it from flow control.
118. Describe slow start, congestion avoidance, fast retransmit, and fast recovery at a conceptual level.
119. What is a socket? Explain the client-server socket model.
120. Explain ephemeral ports and well-known ports.
121. Why might UDP be suitable for DNS, voice, or real-time games? Discuss trade-offs.
122. Explain head-of-line blocking in the context of reliable ordered byte streams.
123. Describe how packet loss and high round-trip time can affect TCP throughput.

### Practical tasks
124. Use ss -tulpen (or an equivalent tool) to list listening TCP/UDP sockets on your own machine.
125. Use Wireshark to capture a TCP connection and label SYN, SYN-ACK, ACK, data, and connection termination where visible.
126. Write a TCP echo server and client in Python or C; handle clean disconnects and basic errors.
127. Write a UDP client-server pair that sends a message and returns a response.
128. Modify the client to use a timeout and explain what happens when the server is unavailable.
129. Use a local test server to compare connection behavior for TCP and UDP; do not generate disruptive traffic.
130. Inspect local listening ports and map each to its process where permissions allow.