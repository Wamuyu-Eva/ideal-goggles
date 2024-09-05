## <span style="color:royalblue;"> INTRO </span>

### Definition of Computer Networking
A collection of computing devices that are logically connected together to communicate and also to share resources. 


___Explaining to shosh and babu:___

_A computer network is like our family where we all have our unique talents like cooking, storytelling and photography e.t.c. Each member is like a helpful buddy and when someone wants to share a great recipe or an interesting story, they just talk to their friend nearby and exchange the ideas. That's it. Its about familty members (devices) in our family (network) talking to each other and sharing their wonderful talents to make things more enjoyable for everyone._


### Elements of Computer Network


#### 1. Computers:
A digital device that processes data to information. 


#### 2. Transmission Medium:
Means of sending data. Could be wired/Guided or wireless/unguided.
Wired for instance Twisted Pair Cable, Coaxial Cable and Optical Fiber Cable.
Wireless like Radiowaves, Microwaves and infrared.


#### 3. Protocols:
Protocols are defined rules governing communication between network devices. They encompass mechanisms for device identification, establishing connections, and formatting rules dictating how data is packaged in messages. Protocols fall into three categories: Internet Protocols, Wireless Network Protocols, and Network Routing Protocols.

#### 4. Network Software:
Foundational for any network, network software aids administrators in deploying, managing, and monitoring the network. Traditionally, networks relied on specialized hardware like routers and switches with embedded software. In the evolution of computer networks, Software-Defined Networking (SDN) emerged, separating software from hardware for increased adaptability to network dynamics.
[1]


### The OSI Model

Open Systems Interconnection (OSI) model is a framework used to understand and describe how different networking protocols interact within a network. 

It consists of seven layers and each represents a specific level of abstraction which has functions and responsibilties of network protocols. 

#### Layers
___Top To Bottom:___


| #   | Item          | Description                                                                                                |
| --- | ------------- | ---------------------------------------------------------------------------------------------------------- |
| 7   | Physical      | Describes the physical components of the network, like the fiber optic cable used in Fiber Distributed Data Interface (FDDI) networks. |
| 6   | Data Link     | Ensures reliable data delivery across the physical layer, typically known for its inherent unreliability.       |
| 5   | Network       | Manages connections to other machines within the network.                                                   |
| 4   | Transport     | Ensures error-free data transmission between devices.                                                      |
| 3   | Session       | Manages the connections established between applications.                                                   |
| 2   | Presentation  | Ensures consistent data presentation to applications.                                                        |
| 1   | Application   | Encompasses the applications utilizing the network services.                                                |



#### Alternative models: 
The TCP/IP Model with 5 layers: Physical, data link, network, transport and application. 


### More Info On Main Networking Components

**Client:** A device or software application that requests and receives services or resources from a server.


**NIC (Network Interface Card):** Hardware component that allows a device to connect to a network, facilitating communication.

**Network Cables:** Physical cables (e.g., Ethernet cables) used to transmit data between network devices.

**Switch:** Networking device that connects multiple devices within a local network, intelligently forwarding data based on MAC addresses.

**Router:** Device that connects different networks, directing data between them and managing traffic based on IP addresses.

**Server:** A computer or system that provides services, resources, or data to clients in a network.




### References
[1]pp pankaj, “Elements of Computer Network,” GeeksforGeeks, Mar. 05, 2019. Available: https://www.geeksforgeeks.org/elements-of-computer-network/


