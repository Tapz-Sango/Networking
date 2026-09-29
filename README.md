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
DEVICE
  ↓
IP
  ↓
SUBNET
  ↓
GATEWAY
  ↓
ROUTE
  ↓
DNS
  ↓
PORT
  ↓
FIREWALL
  ↓
SERVICE

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
