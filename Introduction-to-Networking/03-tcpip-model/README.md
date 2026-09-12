# 03. TCP/IP Model

The **TCP/IP Model** (Transmission Control Protocol/Internet Protocol) is a practical, 4-layer model that is the actual foundation of the modern Internet.

## The 4 Layers

| Layer | Function | Example Protocols |
|-------|----------|-------------------|
| Application | Combines OSI's Application, Presentation, Session layers — handles user-facing services | HTTP, FTP, SMTP, DNS, Telnet |
| Transport | End-to-end communication, reliability | TCP, UDP |
| Internet | Logical addressing, routing | IP, ICMP, ARP |
| Network Access (Link) | Combines OSI's Data Link + Physical — handles physical transmission | Ethernet, Wi-Fi |

## OSI vs TCP/IP — Comparison

| OSI Model (7 Layers) | TCP/IP Model (4 Layers) |
|-----------------------|--------------------------|
| Application | Application |
| Presentation | Application |
| Session | Application |
| Transport | Transport |
| Network | Internet |
| Data Link | Network Access |
| Physical | Network Access |

## Key Differences

| Point | OSI Model | TCP/IP Model |
|-------|-----------|---------------|
| Layers | 7 | 4 |
| Approach | Theoretical/reference model | Practical, implemented model |
| Development | Developed by ISO | Developed by DoD (US) |
| Usage | Used for understanding concepts | Used in real-world Internet |
| Reliability | Layer-independent | Reliability handled by TCP at Transport layer |

## Why TCP/IP Matters
It is the protocol suite that powers the **entire Internet** — every website visit, email, and file download relies on TCP/IP.
