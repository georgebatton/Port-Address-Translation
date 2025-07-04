# Port Address Translation (Dynamic PAT) Lab -CCNA 

Tools used **: Cisco Packet Tracer
Topics Covered**: Inside and Outside Local addresses, Inside and Outside Global IP addresses, Port Address Translation


## Topology
-3 PC's
-1 Switch
-1 Router
-1 Server

## Configuration Steps
1. Created Subnets 192.168.1.0/29 and 172.33.1.0/30
2. Assigned ip addresses to PCs, Router, and Server
3. Assigned IP nat Outside to port F0/1 and Inside to F0/0
4. Created Access-List permitting hosts from 192.168.1.0
5. Configured NAT Overload with Outside Global IP 172.33.1.2 on interface F0/1
6. Ping tests between PC 1-3 and to Server 1
   

##File Point to point route.pkt

