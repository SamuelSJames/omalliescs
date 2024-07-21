# High-Level Network Topology (Router on a Stick with ISP Redundancy)

```bash
                          +------------+
                          |   AWS VPN  |
                          +------------+
                          /                     
                         /                       
             +----------------------+   +----------------------+
             |        ISP1          |   |        ISP2          |
             +----------------------+   +----------------------+
                         \                       /
                          \                     /
                           +----------------------+
                           |     Cisco Router     |
                           |  (Router on a Stick) |
                           +----------------------+
                                     ||           
                                     ||            
                                     ||             
           +------------------+ +------------------+ +------------------+
           |    Cisco Switch  | |    LAN VLAN 1    | |    LAN VLAN 11   |
           +------------------+ +------------------+ +------------------+
           | - Port Security   | | - Secure VLAN    | | - Secure VLAN   |
           | - ACLs            | | - Isolation      | | - Isolation     |
           | - QOS             | | - Management     | | - Sales         |
           +------------------+ +------------------+ +------------------+
```
