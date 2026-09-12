# 06. IP Addressing

## What is an IP Address?
An **IP (Internet Protocol) Address** is a unique numerical label assigned to every device connected to a network, used for identification and location addressing.

## IPv4 vs IPv6

| Feature | IPv4 | IPv6 |
|---------|------|------|
| Address Length | 32-bit | 128-bit |
| Format | Decimal (e.g., 192.168.1.1) | Hexadecimal (e.g., 2001:0db8::1) |
| Total Addresses | ~4.3 billion | ~340 undecillion |
| Address Depletion | Yes (running out) | No (practically unlimited) |
| Header Complexity | Simple | More complex, more efficient |
| Security | Optional (IPSec) | Built-in (IPSec mandatory) |

## IPv4 Classes

| Class | Range | Used For |
|-------|-------|----------|
| A | 1.0.0.0 – 126.255.255.255 | Large networks |
| B | 128.0.0.0 – 191.255.255.255 | Medium networks |
| C | 192.0.0.0 – 223.255.255.255 | Small networks |
| D | 224.0.0.0 – 239.255.255.255 | Multicasting |
| E | 240.0.0.0 – 255.255.255.255 | Experimental/Research |

## Public vs Private IP

| Type | Description | Example Range |
|------|-------------|----------------|
| Public IP | Globally unique, used on the Internet | Assigned by ISP |
| Private IP | Used within local networks, not routable on the Internet | 10.0.0.0 – 10.255.255.255, 192.168.0.0 – 192.168.255.255 |

## Subnetting (Basic Idea)
**Subnetting** divides a large network into smaller sub-networks (subnets) to:
- Improve network performance
- Enhance security
- Efficiently use IP address space

Example: `192.168.1.0/24` means the first 24 bits are the network portion, leaving 8 bits (256 addresses) for hosts.

## Static vs Dynamic IP

| Type | Description |
|------|-------------|
| Static IP | Manually assigned, doesn't change |
| Dynamic IP | Automatically assigned by DHCP, can change over time |
