Networking Lab Report: Wireshark Basics


Objective


The purpose of this lab is to learn basic networking concepts and use Wireshark to capture and analyze live network traffic. Key goals include:
- Understanding IP, MAC, DNS, TCP/UDP.
- Capturing packets with Wireshark.
- Filtering traffic by protocol.
- Observing the TCP three-way handshake.
- Identifying plain-text vs encrypted traffic.
- Analyzing DNS queries.
- Saving packet captures.
- Writing clear observations.

Step 1: Basic Networking Concepts
- IP Address: Identifies a device on the network (like a home address).
- MAC Address: Unique hardware identifier for a network card.
- DNS: Translates domain names (e.g., google.com) into IP addresses.
- TCP: Reliable, connection-oriented protocol (used for web browsing, email).
- UDP: Fast, connectionless protocol (used for streaming, gaming).

Step 2: Installing Wireshark
- Downloaded Wireshark from wireshark.org.
- Installed and opened the application.
- Selected the active network interface (Wi-Fi).
- Started live packet capture.

Step 3: Filtering Packets
- Applied filters to focus on specific protocols:
- http → showed web traffic.
- dns → showed DNS queries.
- tcp → showed TCP connections.

Step 4: TCP Three-Way Handshake
Observed the handshake sequence:
- SYN: Client requests connection.
- SYN-ACK: Server acknowledges.
- ACK: Client confirms.
This establishes a reliable TCP connection.

Step 5: Plain-Text vs Encrypted Traffic
- HTTP traffic: Readable text (URLs, headers).
- HTTPS traffic: Encrypted, content unreadable. Only metadata (IP, port) visible.

Step 6: DNS Queries
- Filtered with dns.
- Saw queries like: A google.com.
- Response contained IP address of google.com.
- This shows how DNS resolves names into IPs.

Step 7: Saving Captures
- Used File → Save As.
- Saved capture as .pcapng file.
- File can be reopened later for deeper analysis.

Step 8: Observations (Simple Language)
- "My computer asked DNS for google.com and got back an IP address."
- "The TCP handshake had three steps: SYN, SYN-ACK, ACK."
- "HTTP traffic was readable, but HTTPS traffic was encrypted."
- "I saved the capture file for later review."

Conclusion
This lab demonstrated how Wireshark can be used to capture and analyze network traffic. I learned the difference between plain-text and encrypted traffic, how DNS queries work, and how TCP establishes connections. Saving captures allows further study and practice.
