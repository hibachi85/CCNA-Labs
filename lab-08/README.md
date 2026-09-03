# IP configurations

## the senario:
A small network contains three local networks that are connected to R1

## devices:
* Cisco Router 2911 (1)
* Cisco switches 2960-24TT (x3)
* PC (end hosts) (x3)

## The process:
* I assigned an IPv4 Class A address to the first port of the R1 Gi0/0 and wrote a description that indicates that this interface is connected to SW1
* I assigned an IPv4 Class B address to the second port of the R1 Gi0/1 and wrote a description that indicated that this interface is connected to SW2
* I assigned an IPv4 Class C address to the third port of the R1 Gi0/1 and wrote a description that indicated that this interface is connected to SW3
* I saved the running configuration to a startup configuration
* I assigned an IPv4 Class A address to PC1
* I assigned an IPv4 Class B address to PC2
* I assigned an IPv4 Class C address to PC3
* I checked the network connection between PC's


___
## files connected to the lab
* topology.png
* topology.pkt
