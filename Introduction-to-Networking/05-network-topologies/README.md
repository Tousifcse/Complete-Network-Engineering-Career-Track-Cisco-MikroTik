# 05. Network Topologies

A **topology** describes how devices in a network are physically or logically arranged.

## Types of Topologies

### 1. Bus Topology
All devices are connected to a single central cable (the "bus").
- ✅ Easy and cheap to install
- ❌ Entire network fails if the main cable breaks

### 2. Star Topology
All devices connect to a central device (hub/switch).
- ✅ Easy to manage, one device failure doesn't affect others
- ❌ If the central device fails, the whole network goes down

### 3. Ring Topology
Devices are connected in a circular fashion, data travels in one (or both) direction(s).
- ✅ Equal access for all devices, no data collisions
- ❌ One broken connection can disrupt the entire network

### 4. Mesh Topology
Every device is connected to every other device.
- ✅ Highly reliable, no single point of failure
- ❌ Expensive and complex to set up (needs lots of cabling)

### 5. Tree Topology
A hybrid of star and bus — groups of star networks connected to a central bus.
- ✅ Scalable, easy to expand
- ❌ Depends heavily on the main bus cable

### 6. Hybrid Topology
A combination of two or more different topologies.
- ✅ Flexible and scalable
- ❌ Complex design and higher cost

## Comparison Table

| Topology | Cost | Reliability | Scalability | Fault Tolerance |
|----------|------|-------------|--------------|------------------|
| Bus | Low | Low | Low | Poor |
| Star | Medium | High | High | Good |
| Ring | Medium | Medium | Medium | Poor |
| Mesh | High | Very High | Low | Excellent |
| Tree | Medium | Medium | High | Moderate |
| Hybrid | High | High | High | Good |
