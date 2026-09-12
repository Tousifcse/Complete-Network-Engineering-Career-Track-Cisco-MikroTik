# 08. Networking Protocols

A **protocol** is a set of rules that governs how data is transmitted and received over a network.

## Common Protocols

| Protocol | Full Form | Function | Port |
|----------|-----------|----------|------|
| HTTP | HyperText Transfer Protocol | Transfers web pages | 80 |
| HTTPS | HTTP Secure | Secure version of HTTP (encrypted) | 443 |
| FTP | File Transfer Protocol | Transfers files between computers | 20, 21 |
| SMTP | Simple Mail Transfer Protocol | Sends email | 25 |
| POP3 | Post Office Protocol v3 | Retrieves email from server | 110 |
| IMAP | Internet Message Access Protocol | Retrieves and manages email on server | 143 |
| DNS | Domain Name System | Translates domain names to IP addresses | 53 |
| DHCP | Dynamic Host Configuration Protocol | Automatically assigns IP addresses | 67, 68 |
| Telnet | — | Remote login (unencrypted) | 23 |
| SSH | Secure Shell | Secure remote login (encrypted) | 22 |
| ARP | Address Resolution Protocol | Maps IP address to MAC address | — |
| ICMP | Internet Control Message Protocol | Error reporting (used by `ping`) | — |

## TCP vs UDP

| Feature | TCP | UDP |
|---------|-----|-----|
| Full Form | Transmission Control Protocol | User Datagram Protocol |
| Connection | Connection-oriented | Connectionless |
| Reliability | Reliable (acknowledgments, retransmission) | Unreliable (no acknowledgment) |
| Speed | Slower | Faster |
| Ordering | Maintains order of data | No guarantee of order |
| Use Case | Web browsing, email, file transfer | Video streaming, gaming, VoIP |

## How DNS Works (Simplified)
1. User types a domain name (e.g., google.com)
2. Browser asks DNS resolver for the IP address
3. DNS resolver checks cache, or queries root/TLD/authoritative servers
4. IP address is returned to the browser
5. Browser connects to the server using the IP address
