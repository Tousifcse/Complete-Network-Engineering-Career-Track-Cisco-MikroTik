# 02. OSI Model (Open Systems Interconnection)

The **OSI Model** is a conceptual framework with **7 layers** that standardizes how different networking systems communicate.

## The 7 Layers (Top to Bottom)

| Layer No. | Layer Name | Function | Example Protocols/Devices |
|-----------|-----------|----------|---------------------------|
| 7 | Application | Interface between user and network; provides network services to apps | HTTP, FTP, SMTP, DNS |
| 6 | Presentation | Data translation, encryption, compression | SSL/TLS, JPEG, ASCII |
| 5 | Session | Establishes, manages, and terminates sessions between devices | NetBIOS, RPC |
| 4 | Transport | Reliable data delivery, error checking, flow control | TCP, UDP |
| 3 | Network | Logical addressing and routing of packets | IP, ICMP, Routers |
| 2 | Data Link | Physical addressing (MAC), error detection at frame level | Ethernet, Switches, MAC address |
| 1 | Physical | Transmission of raw bits over physical medium | Cables, Hubs, NICs |

## Easy Way to Remember (Mnemonic)
**"All People Seem To Need Data Processing"**
(Application → Presentation → Session → Transport → Network → Data Link → Physical)

## How Data Flows (Encapsulation)
When data is sent, it moves **down** the layers on the sender's side (Application → Physical), getting wrapped with headers at each layer. On the receiver's side, it moves **up** the layers (Physical → Application), where headers are removed (**decapsulation**).

```
Sender:   Application → Presentation → Session → Transport → Network → Data Link → Physical
                                                                                          |
                                                                                    (transmission)
                                                                                          |
Receiver: Application ← Presentation ← Session ← Transport ← Network ← Data Link ← Physical
```

## Why OSI Model is Important
- Provides a universal standard for networking
- Helps in troubleshooting network issues layer by layer
- Makes it easier to understand how different protocols interact
