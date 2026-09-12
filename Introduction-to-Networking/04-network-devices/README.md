# 04. Network Devices

## Common Networking Devices

| Device | Function | OSI Layer |
|--------|----------|-----------|
| **Hub** | Broadcasts data to all connected devices; no intelligence | Physical (Layer 1) |
| **Switch** | Forwards data only to the intended device using MAC address | Data Link (Layer 2) |
| **Router** | Connects different networks; routes data using IP address | Network (Layer 3) |
| **Bridge** | Connects two LAN segments, filters traffic by MAC address | Data Link (Layer 2) |
| **Gateway** | Connects networks using different protocols; acts as an entry/exit point | All Layers |
| **Access Point (AP)** | Allows wireless devices to connect to a wired network | Data Link (Layer 2) |
| **Modem** | Converts digital signals to analog and vice versa (for internet via telephone/cable line) | Physical (Layer 1) |
| **Repeater** | Amplifies/regenerates signal to extend network range | Physical (Layer 1) |
| **NIC (Network Interface Card)** | Hardware that connects a computer to a network | Data Link (Layer 2) |
| **Firewall** | Monitors and filters incoming/outgoing traffic for security | Network/Transport |

## Hub vs Switch vs Router — Quick Comparison

| Feature | Hub | Switch | Router |
|---------|-----|--------|--------|
| Layer | Physical | Data Link | Network |
| Intelligence | None | Uses MAC address | Uses IP address |
| Data Sent To | All ports | Specific device | Specific network |
| Speed | Slow | Fast | Moderate |
| Collision Domain | Single | Separate per port | Separate per port |

## Notes
- A **switch** is generally used within a single network (LAN) to connect devices.
- A **router** is used to connect multiple networks together (e.g., your home network to the Internet).
