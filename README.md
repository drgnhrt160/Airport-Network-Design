# Airport-Network-Design

A proposed network architecture for an airport demonstrated using cisco packet tracer.

An airport which has three departments, i.e., the airport authority, flight service providers and guests. The airport authority maintains a server which handles the flight management controls. 

The flight service providers have access only to the specific server in the airport authority and not to any other systems. The guest users have access to a high-speed internet connection which is shared among all the users in all the departments, the wireless access also uses a common password. 

The guest users do not have any access to the other two departments and all users of every department obtain IP addresses automatically with the help of DHCP, enabled by the server they are connected to. 

The topology used to design the network is Hybrid Topology, it consists of different star topologies, which in turn can be connected to other smaller networks. A total of four VLANs are used in the network, one for the main switch and the Airport Authority Server, and the rest for Airport Authority, Flight Service Providers and Guests respectively. 

This sums up the basic infrastructure and network design for this project.

![WhatsApp Image 2021-05-27 at 2 43 11 AM](https://user-images.githubusercontent.com/52793422/119832223-9e8d1380-bf1b-11eb-8f9e-42b2c498b83c.jpeg)
![image](https://user-images.githubusercontent.com/43717289/119832928-486ca000-bf1c-11eb-884f-a9a24e6cf4a5.png)
