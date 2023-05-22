# Packet-tracer-part C

## PART C
 To get started with Part C, we used packet tracer because time did not permit us to do it in class. We used the multilayer switches (Cisco 3560), since there is no 3750s on packet tracer. We established two switches for part C and provided three hosts for each switch. We made a connection from switch 1 to switch 2. Picture shown below.

![Picture1](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/8bb7eb0b-58eb-47ef-b3e2-37929222a0fa)

After creating the platform, we began to configure and establish the connection. We went into switch 1 and created a hostname for it (lower room), created three Vlan’s, not including Vlan1. We assigned each Vlan its own IP address, giving Vlan1 76.100.10.1 255.255.252.0. The other Vlan’s were given different IP addresses but with the same subnet mask. We assign each vlan 7 ports. We did the same for switch 2 but used a different network address, which was 78.100.48.0/21. We assigned switch 2 (upper room) vlan 1 the IP address of 78.100.48.1 255.255.248.0. As shown below. 

![Picture2](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/f3e5609e-23ab-4dc4-bc0c-057c1287f4c6)  

![Picture3](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/e1854fcf-f63e-4f81-ade0-8a9b443edb50)

We made port 24 act like a router and gave it is own network. Which was 10.10.10.3 255.255.255.0 for switch 1 and for switch 2 it was 10.10.10.2 255.255.255.0

![Picture4](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/23be6cc0-cce8-4530-8563-964ea96074a8)   ![Picture5](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/d704aa7f-02fa-40ae-a384-465277bafd01)

Once we finished this, we had to make the switches act like a router. This allowed us to use RIP, so that both switches can communicate with each other even though they are in different networks.

![Picture6](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/81faf26c-a1d9-40d4-a809-a905c4211c29)  ![Picture7](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/8e2acf7a-439c-40d0-a905-cb5606b47b96)

After this long process, we were able to ping switch to switch, ping switch to host, host from sw1 to host sw2,  host to network 24 (port 24) and Switch to network 24 (port24).

![Picture8](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/b1e89c90-d94f-486d-bff6-e0d813a75c12)  ![Picture9](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/6fb4398f-edb7-41fa-a529-7b05ed8c34e5)

![Picture10](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/fcd2c2f9-fd79-484d-b55b-c55aa6925daa)   ![Picture11](https://github.com/aissatoubarry938/Packet-tracer-partC/assets/115582067/93f4984a-4548-4859-9fc7-36a4f2523344)

