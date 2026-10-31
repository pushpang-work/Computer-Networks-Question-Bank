# PART C — DATA LINK LAYER, ETHERNET, AND SWITCHING

### Theory questions
37. What services does the data link layer provide?
38. Explain framing and why receivers need frame boundaries.
39. Compare MAC addresses and IP addresses.
40. Explain parity, checksum, and cyclic redundancy check (CRC).
41. Describe Hamming distance and how Hamming codes can detect or correct errors.
42. Explain Stop-and-Wait flow control and its efficiency limits.
43. Compare Stop-and-Wait ARQ, Go-Back-N ARQ, and Selective Repeat ARQ.
44. Explain sliding-window protocols and cumulative acknowledgements.
45. Describe CSMA/CD and explain its historical role in shared Ethernet.
46. Describe CSMA/CA and its use in Wi-Fi.
47. Explain Ethernet frame fields and the role of the FCS.
48. What is a switch MAC address table, and how does a switch learn addresses?
49. Explain VLANs, access ports, trunk ports, and 802.1Q tagging.
50. What problem does Spanning Tree Protocol solve?
51. Compare a hub, bridge, switch, router, and access point.

### Practical tasks
52. Build a switched LAN with four PCs and verify connectivity using ICMP.
53. Inspect a packet capture and identify Ethernet source/destination MAC addresses and EtherType.
54. Create two VLANs in a simulator, assign ports, and verify that hosts in different VLANs cannot communicate without routing.
55. Configure a trunk link between two switches in a simulator and test VLAN connectivity.
56. Observe a switch's MAC address table in a simulator or managed switch and explain how entries are learned.
57. Demonstrate a CRC or parity calculation on a small binary data example, showing each step.
58. Create a simple topology with redundant switch links and explain how STP prevents a loop; use a simulator if needed.