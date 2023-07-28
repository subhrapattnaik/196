# 196

TOPOLOGIES

https://www.geeksforgeeks.org/types-of-network-topology/


learn about different types of connections between the computers.

 learn about topologies and to create the topologies.


————————————
In the last class we learned to set up a router and connect multiple LAN’s with it.
We learned about the default gateway too
——————————————————

Topology is the way in which constituent parts are interrelated or arranged. 


 One of the examples of a topology is a LAN that we have created earlier .

 This type of topology comes under network topology.

 Network topology is the arrangement of elements of a communication network.
 All the devices which receive and send data are part of this topology.

——————————————————————————————————
A topology consists of two parts :

 a) Physical topology which includes the placement of the various types of components such as devices and cable installations.
b) Logical topology illustrates how the data flows in a network.

————————————————————————————
Network topology is the arrangement of the elements of a communication network. Network topology can be used to define or describe the arrangement of various types of telecommunication networks, including command and control radio networks, industrial field busses and computer networks.

——————————————————————
This is one type of topology called a bus topology. The bus topology is designed in such a way that it connects all the stations/switches through a single cable which is also called the backbone cable. As we see here each node is either connected to the backbone cable by another drop cable or directly connected to the backbone cable.

——————————————————————————————
open cisco packet tracer. 

 in bus topology all the nodes are connected by one single cable which is called the backbone cable.

In this topology when a node/PC wants to send the message over the network, it puts a message over the network and all the stations available in the network will receive the message whether it has been addressed or not as the backbone cable is considered as a “single lane” through which the message is broadcast to all the stations.

Each topology has it’s advantages and disadvantages. 

The advantages are:-
 ● Low-cost cable: In bus topology, nodes are directly connected to the cable without passing through a hub. Therefore, the initial cost of installation is low. 

● Moderate data speeds: Coaxial or twisted pair cables are mainly used in bus-based networks that support upto 10 Mbps.

 ● Familiar technology: Bus topology is a familiar technology as the installation and troubleshooting techniques are well known, and hardware components are easily available. 

● Limited failure: A failure in one node will not have any effect on other nodes. 


------------------------------------------------------
The disadvantages are:- 

● Extensive cabling: A bus topology is quite simpler, but still it requires a lot of cabling. 

● Difficult troubleshooting: It requires specialized test equipment to determine the cable faults. If any fault occurs in the cable, then it would disrupt the communication for all the nodes. 

● Signal interference: If two nodes send the messages simultaneously, then the signals of both the nodes collide with each other. 

● Reconfiguration is difficult: Adding new devices to the network would slow down the network. 

● Attenuation: Attenuation is a loss of signal that leads to communication issues. Repeaters are used to regenerate the signal.





 To create this topology we’ll be needing couple of devices which are :- 
1. Switch, which will act as the nodes. 
2. Computers or laptops, which will be connected to these nodes. 
3. Wires to create the connections.

[We need to join these switches using the cable. On the panel below we see the thunderbolt icon. When we press it we see different types of the cables. If we again click on the thunderbolt icon on the right panel and then click on the two switches it will select the correct cable automatically for us.

Let’s add the devices to the canvas and connect them with the switches.

]





add the IP address for each of the end devices.

Now let’s test the topology by sending some packets from PC0 to Laptop0.
Click on the envelope icon and then click on one of the pc from where you want to send the packet
Then click on the other PC which you want to receive these packets.
Now to see the whole steps in the simulation we just need to click on the next button.
Click the next button to see the transfer of packets.
—————————————————————————————
As we have studied earlier about
 the bus topology that it broadcasts the packets to all the connected devices. 
So the packets got sent to PC1 even when it was not the receiver.
 When the same amount of packets return back to the sender we know that the connection is proper and strong and there is no data/packet loss.
————————————————————————
So we can see that the topology that we have created works properly.
———————————————————
**************************************
Ring Topology :
-------------------

 the shape / structure of this topology would be circular i.e it would be connected at all ends
 in a circle.
Ring topology is like a bus topology, but with connected ends. 
The node that receives the message from the previous computer will retransmit to the next node. 
The data flows only in one direction i.e it’s unidirectional. The data in the ring topology flows in a clockwise direction.

The most common access method of the ring topology is token passing. 

● Token passing: It is a network access method in which a token is passed from one node to another node. 

● Token: It is a frame that circulates around the network.
It contains the packets/data and the address of the receiver.

This token is passed from computer to computer until it reaches the destination.

 The sender modifies the token by putting the address along with the data.
The data is passed from one device to another device until the destination address matches. 
Once the token is received by the destination device, then it sends the acknowledgment to the sender.

———————————————————
the advantages and disadvantages of the ring topology? 

Advantages:-

 Network Management: Faulty devices can be removed from the network without bringing the network down. 

Product availability: Many hardware and software tools for network operation and monitoring are available.

Disadvantages:
Difficult troubleshooting: It requires specialized test equipment to determine the cable faults. If any fault occurs in the cable, then it would disrupt the communication for all the nodes. 

Failure: The breakdown in one station leads to the failure of the overall network. Reconfiguration is difficult: Adding new devices to the network would slow down the network.


—————————————————————————————

let’s create

Let’s create this using 4 switches and  end devices.


We need to connect the devices with the wires and add IP to the end devices.
Now we just need to test this topology.
--------------------------------------------------------
Let’s test it by sending the data from PC3 to PC6.

Select the envelope sign
Click on the PC3 as sender and PC6 as receiver.
Click on simulation to see the simulation. And use the forward button to play the simulation.
Data moving from switch 0 to switch 1.
Data moving from Switch 1 to switch 2.
Data moving from Switch 2 to switch 3.
Data moving from switch3 to PC6.
Note:- As you continue the simulation you can see the data being sent back the same path.
--------------------------------------------------------------

