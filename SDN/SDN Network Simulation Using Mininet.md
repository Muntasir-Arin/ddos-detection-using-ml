Title: SDN Network Simulation Using Mininet

Objective:
This project involves setting up a basic network topology using Mininet to simulate SDN network environments for testing and experimentation.

Network Setup:

Topology: The network consists of two hosts (h1, h2), one Open vSwitch bridge (s1), and a controller.
Links: Host h1 is linked to switch s1 via h1-eth0:s1-eth1, and host h2 is linked to switch s1 via h2-eth0:s1-eth2.
Addresses: Host h1 is assigned IP address 10.0.0.1, and host h2 is assigned IP address 10.0.0.2.

Command Log
Mininet Initialization: Upon initializing Mininet, the network was set up, with hosts and switches added. 

Network Configuration: The network was configured with the following layout:
h1 connected to s1 via s1-eth1
h2 connected to s1 via s1-eth2

CLI Operations:

sudo mn: Initialization

net: Displayed the host and switch

dump: Displayed the state of the network, including host information and switch connections.

pingall: Confirmed network reachability between hosts. Results showed 0% packet loss, indicating successful connectivity.

xterm h1, h2: It opened two terminal for the two hosts.

wireshark: Opened wireshark to view the traffics.

Remarks:
The basic topology setup was successful with two hosts and one switch. 

Visualization:
For visualizing the topology, miniedit was used.
