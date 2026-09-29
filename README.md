## Project:
Small Enterprise Network

## Networks:
- 192.168.10.0/24 - Users
- 192.168.20.0/24 - Servers
- 192.168.30.0/24 - Management

## Technologies:
- Cisco Packet Tracer
- IPv4
- Subnetting
- Routing
- DHCP
- DNS concepts
- Network troubleshooting

## Troubleshooting steps:


                 Problem
                    ↓
          Is the device connected?
                    ↓
            Does it have an IP?
                    ↓
        Is the IP/subnet correct?
                    ↓
          Is the gateway correct?
                    ↓
       Can it reach the gateway?
                    ↓
        Can it reach the destination?
                    ↓
           Is routing correct?
                    ↓
              Is DNS working?
                    ↓
           Is the port accessible?
                    ↓
            Is firewall allowing it?
                    ↓
            Is the service running?

1. Physical / interface
2. IP address
3. Subnet
4. Default gateway
5. Local connectivity
6. Routing
7. DNS
8. Ports
9. Firewall
10. Application/service

## Topology

                         ROUTER
                       /    |    \
                      /     |     \
                     /      |      \
                 Switch1   Switch2   Switch3
                    |         |         |
                  USERS     SERVERS   MANAGEMENT
                 /     \       |         |
               PC1     PC2   Server     Admin PC
