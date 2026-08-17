# lab-02
Focuses on the wire types used to connect a network

## objective 
This lab focuses on foundational networking and cable types (UTP cable, fiber-optic cable) and which cable must be used in each condition

## Scenario & Architecture
Connect the network devices according to the labels.\
1. R1 to R3: they are 3 kilometers apart, so I used single-mode fiber-optic cable
2. R1 and R2: they are 50 meters apart, so I used a cross-over UTP copper cable (because they are two routers, which means their transmitting and receiving pins are the same, so they need a crossover cable, UTP because the distance isn't that long)
3. R3 to R4: they are 250 meters apart, so I used multimode fiber optic cable
4. At the switches level, I connected each device with the other opropiate one. I only used UTP cable because the distance isn't long between the devices,
5. I used crossover UTP cables with (SW1-SW2 / SW3-SW4/ SW1-SW3 / SW2-SW4/ SW5-SW6 / SW5-SW7/SW6-SW8/ SW7-SW)
6. I used a straight-through UTP cable to connect the routers to the switches(R2-SW/R2-SW2/R4-SW5/R5-Sw6), then the switches to the host ends (PC1-SW1 / PC2-SW4 / PC3-SW7 / SRV1-SW8)

## Network devices used:
* Routers (x4)
* Switches (x8)
* PCs(x3)
* Server (1)

____
* Files included in this folder:*
* 'topology.png' (Network Topology Diagram)
* 'topology.png' (Cisco Packet Tracer file)
