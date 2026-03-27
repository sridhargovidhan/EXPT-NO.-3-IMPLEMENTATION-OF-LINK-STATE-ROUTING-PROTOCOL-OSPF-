# EXPT NO.3 IMPLEMENTATION OF LINK STATE ROUTING PROTOCOL OSPF
# AIM

To connect computers in multiple networks using Open Shortest Path First Routing Protocol and to verify the connectivity between computers.

# EQUIPMENTS REQUIRED
Pc With Cisco Packet Tracer
# IP ASSIGNMENT
| NAME     | IP ADDRESS      | SUBNET MASK     | NETWORK       | CLASS | GATEWAY         |
|----------|------------------|------------------|---------------|-------|------------------|
| PC0      | 192.168.0.1      | 255.255.255.0    | 192.168.0.0   | C     | 192.168.0.200    |
| PC1      | 192.168.0.2      | 255.255.255.0    | 192.168.0.0   | C     | 192.168.0.200    |
| PC2      | 192.168.1.1      | 255.255.255.0    | 192.168.1.0   | C     | 192.168.1.200    |
| PC3      | 192.168.1.2      | 255.255.255.0    | 192.168.1.0   | C     | 192.168.1.200    |
| PC4      | 192.168.2.1      | 255.255.255.0    | 192.168.2.0   | C     | 192.168.2.200    |
| PC5      | 192.168.2.2      | 255.255.255.0    | 192.168.2.0   | C     | 192.168.2.200    |
| ROUTER0  | 192.168.0.200    | 255.255.255.0    | 192.168.0.0   | C     | -                |
| ROUTER0  | 192.168.1.200    | 255.255.255.0    | 192.168.1.0   | C     | -                |
| ROUTER1  | 192.168.1.201    | 255.255.255.0    | 192.168.1.0   | C     | -                |
| ROUTER1  | 192.168.2.200    | 255.255.255.0    | 192.168.2.0   | C     | -                |



# NETWORK DIAGRAM

<img width="1280" height="726" alt="image" src="https://github.com/user-attachments/assets/24a611fa-297f-4d51-b3e8-1fa918944878" />



# PROCEDURE
STEP 1: Open a Packet Tracer Software.
STEP 2: Drag two 2900 Switches, two Cisco 1800 Routers, four PC Terminals from tool bar and drop it in work area.
STEP 3: Connect all the PC Terminals and Routers through Switches as shown in the network diagram using CAT 6 Patch cables.
STEP 4: Configure IP address and Gateway in all PC Terminals.
STEP 5: Configure Delhi router IP address, save configuration and restart Delhi router. STEP 6: Configure Chennai router IP address, save configuration and restart Chennai router. STEP 7: Check the connectivity between the computers in network.
STEP 8: Configure OSPF in Delhi router, Save configuration and restart Delhi router.
STEP 9: Configure OSPF in Chennai router, Save configuration and restart Chennai router.
STEP 10: Verify the connectivity between PC Terminals in different networks using Ping command.
STEP 11: Check the routing table in Delhi router and Chennai router using show ip route command

# OUTPUT
<img width="1280" height="726" alt="image" src="https://github.com/user-attachments/assets/39610f8d-51c3-4981-8739-4eaa86aa8130" />
<img width="1035" height="1038" alt="image" src="https://github.com/user-attachments/assets/ce2a9d80-8580-40dd-aabb-baa25ec57a74" />





# RESULT
Thus the computers in multiple networks using Open Shortest Path First Routing Protocol is connected and the connectivity between the computers is verified.

