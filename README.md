# Transparent Ethernet/IPv4 Loadbalancer
Old student project from Lulea University of Technology.
Report [rapport-lb.pdf](rapport-lb.pdf) describes an FPGA based Ethernet/IPv4
capable FPGA design written in VHDL that processed:
 - Ethernet
 - Address Resolution Protocol (ARP)
 - Internet Protocol (IPv4)

The main contribution was to make a cluster of servers with the same IP address
appear as a singel Ethernet device over Ethernet/ARP, using various network
protocol hacks, simple RTL logic, and no advanced processing.

Diagram:
(network) <-> Load Balancer <-> Switch <-> Servers

The solution was successfully demoed against various TCP protocols and
artifical load / stress tests.  The solution has never been used outside of
demo/laboritory environments, i.e. it was not verified reliable in a real world
production environment.

# Abstract
This paper outlines the design decisions behind the development of an OSI Layer 
2 and 3 "Transparent Loadbalancer", and the reasons behind those design de- 
cisions. The loadbalancer was implemented in a Xilinx XCV1000 FPGA. The 
project has been carried out by undergraduate students as a part of the Digital 
Synthesizes course held in 2001 at Lulea University of Technology LUTH by 
the Department of Computer Science And Electrical Engineering CSEE in co- 
operation with Switchcore SWCR, an ASIC design company which specializes 
in ASICs for fast networks.

# Authors, Contributors
Jens Eliasson
Erik Holmgren
Tim Johansson
Peter Magnusson
Chirstian Nilsson

# Date of Publication 
4th June 2001


