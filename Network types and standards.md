# Network Types, and Standards.

## Terms Relating to Networking

### Services and Network Applications
**FTP**


File Transfer Protocol (FTP) is an internet protocol that is used to transfer files. The files are transmitted via TCP/IP between computers on the internet.

**HTTP**


Hypertext Transfer Protocol (HTTP) is what is sent to a server when you type in an HTTP address. If the link is functional then a copy of the website and any associated files will be sent to your computers webpage.  

**SMTP**


Simple Mail Transfer Protocol (SMTP) is used when sending and recieving an email. It is typically used with POP3 or IMAP that save messages to a server mailbox. This protocol is an internet standard for electronic mail. 

**POP3**


Post Office Protocol (POP) is an internet standard protocol. Mail servers use POP to recieve emails from an IP, and filter and catorgorise the mail recieved.+

**SSL**


Secure Socket Layers are used to establish an encrypted link between the web server and the browser. Encrypting the data prevents your privacy from being vulnerable.

## Networking devices
**Hubs**
A hub, also called a network hub, is a common connection point for devices in a network.


**Routers**
A router is a networking device that forwards data packets between computer networks.


**Switches**
A switch is a high-speed device that receives incoming data packets and redirects them to their destination on a local area network (LAN).


**Multiplayer switch**
A multilayer switch is a network device that operates at higher layers of the OSI reference model, unlike the Data Link Layer (DLL) traditionally used by switches.


**Firewall**
A firewall is software or firmware that enforces a set of rules about what data packets will be allowed to enter or leave a network.


**HIDS**
A host-based intrusion detection system (HIDS) is an intrusion detection system that is capable of monitoring and analyzing the internals of a computing system as well as the network packets on its network interfaces, similar to the way a network-based intrusion detection system (NIDS) operates.


**Repeaters**
A network device used to regenerate or replicate a signal. 


**Bridges**
A bridge is a type of computer network device that provides interconnection with other bridge networks that use the same protocol.


**Wireless devices**
Devices with a wifi radio that you use to connect to a wireless access point, e.g. a computer, cell phone or tablet device.


**Access point (wireless/wired)**
An access point is a device, such as a wireless router, that allows wireless devices to connect to a network. Most access points have built-in routers, while others must be connected to a router in order to provide network access.


**Content filter**
Content filtering is used by corporations as part of Internet firewall computers and also by home computer owners, especially by parents to screen the content their children have access to from a computer.


**Load balancer**
Network load balancing (NLB) is the management of traffic across a network without the use of complex routing protocols such as Border Gateway Protocol (BGP).


**Modem**
A modem is a device or program that enables a computer to transmit data over, for example, telephone or cable lines.


**Packet shaper**
The packet shaper is a device that sits in between the campus network and the outside network. All incoming and outgoing traffic passes through it. Its purpose is to classify the traffic passing through, and prioritize that traffic based on rules that we define.


**VPN concentrator**
A VPN concentrator is a type of networking device that provides secure creation of VPN connections and delivery of messages between VPN nodes. It is a type of router device, built specifically for creating and managing VPN communication infrastructures.


## Server types
**Web**
A Web server is a program that uses HTTP (Hypertext Transfer Protocol) to serve the files that form Web pages to users, in response to their requests, which are forwarded by their computers' HTTP clients. Dedicated computers and appliances may be referred to as Web servers as well.


**File**
A file server is a server provides access to files. It acts as a central file storage location that can be accessed by multiple systems.


**Database**
A database server is a server which houses a database application that provides database services to other computer programs or to computers, as defined by the client–server model.


**Combination**
A hybrid hosting service or hybrid server is a type of Internet hosting which is a combination of a physically-hosted server with virtualization technology.


**Virtulisation**
A virtual server is a server that shares hardware and software resources with other operating systems (OS), versus dedicated servers. Because they are cost-effective and provide faster resource control, virtual servers are popular in Web hosting environments.


**Terminal services server**
A terminal server is a hardware device or server that provides terminals (PCs, printers, and other devices) with a common connection point to a local or wide area network. The terminals connect to the terminal server from their RS-232C or RS-423 serial port.


# OSI model
### The Physical Layer (Layer 1)
The first layer of the OSI model is the phisical layer, that transmitts information to the user. This layer will be the first thing the user see's, and interacts with. 

### The Data Link Layer (Layer 2)
This layer creates links between all the repective layers. While doing this it also carries out tasks such as: accessing media, and error correcting.

### The Network Layer (Layer 3)
This layer of the OSI handles traffic the network encounters. It decides, and controls said traffic in the network.

### The Transport Layer (Layer 4)
The transport layer is the fourth layer of the OSI model. It handles traffic and message segmentation. It also makes sure messages reach their desired location, and that no information is lost along the way.

### The Session Layer (Layer 5)
This is the fifth layer of the OSI. It establishes a session, it also handles maintance, and termination of said session.

### The Presentation Layer (Layer 6)
The sixth layer of the OSI model handles the character code translation (I.E ASCII), encryption, and compression.

### The Application Layer (Layer 7)
The seventh layer provides to users: remote access, and network access. The purpose of this layer varies, depnding on the type of application your producing.

# TCP/IP model
### The Link Layer (Layer 1)
This layer combines the physical, and data link layer in the OSI model. This layer is the interface for your network.

### The Internet Layer (Layer 2)
The Internet layer is associated with the network layer from the OSI model. It's functions include: traffic control, traffic routing, fragmentation, and logical addressing.

### The Transport Layer (Layer 3)
Layer 3 shares the same components as the transort layer from the OSI model. These functions include: traffic control, error detection, message segmentation, message recording, and acknowledgment.

### The Application Layer (Layer 4)
The application layer is used to handle all process-to-process communication functions. The functions are carried out by multiple different layers when referencing the OSI model.

# Benefits of TCP/IP and OCI models
### Benefits of the TCP/IP model
- Various different computers can establish a connection.
- Operates indepently from the operating system.
- Supports a number of routing-protocals.
- Enables organisations to connect their networks together.

### Disadvantages of the TCP/IP model
- Complex to set up and manage.
- IPX is faster.

### Benefits of the OCI model
- You are given a wider variety of choice than with TCP/IP model. 
- Doesn't depend on a specific computer system.
- Easy to add multiple-network models.
- Ecrypts data.

### Disadvantages of the OCI model
- Many applications do not require/need the data integrity, which is provided by OSI-model
- Complex.
- OSI requires an agreement between the users & service provider.

# Network types
### Peer-based:
Peer-based, or Peer-to-peer (P2P) is when multiple devices share resources without the use of an external server. P2P is most commonly associated with piracy, and its clear why. P2P networks are made up of many users (ideally) that, while on the server, act as file servers. The things you need to connect to a P2P server is an internet connection, and P2P software.   

**Benefits**
- A peer to peer network is easier to set up.
- All nodes act of a server.
- Cheap to maintain.


**Resource Implications**
You will need two, or more computers to create a P2P network.


**Communications**
Communications will be between the computers connected via P2P.


**Working Practice**
Miminal work involved in the maintenance due to it's simplicity.


**Commercial Opportunity**
Very useful within a business. As it allows you to share files and data between computers on the P2P network. 


**Information Sharing**
If the sending and recieving computer are on the same network, then information can be passed back and forth.


### client-server:
This is the use of a central server that communicates, and shares data with multiple computers on the 
network.


**Benefits**
- Data is shared giving user's the ability to access files and data on the server.  
- Network peripherals are controlled centrally.
- All files are stored in a central location.


**Resource Implications**
You would need a main client which would act as the server, and also other connected client PC's. Once connected, clients will be able to share their data with one another.


**Communications**
Clients communicate with eachother directly due to them being on a client server.


**Commercial Opportunity**
This is good for companies that share data, as it allows user's to easily share between eachother.


### cloud:
Cloud servers are remote servers that are totally virtual. These virtual servers can be purchased for alot cheaper than physical servers.


**Benefits**
- Reduced maintenance costs.
- As its not a phisical object you save on space.
- Can maintain a massive network.
- Can access data from most devices.


**Resource Implications**
To implement a cloud network you will need hardware enabling you to create a virtual network. You will also need a router that will connect to said virtual network.


**Communications**
Because it is wireless it allows users to seamlessly share with eachother other, aslong as they're connected to the same cloud.


**Working Practice**
While using a cloud network you can create firewall's for your virtual network making it more secure. This is very important for buisnesses due to sensitive information that may be shared.


**Commercial Opportunity**
Information stored on the cloud can be accesses from anywhere. This allows for companies, employees to easily collaborate with eachother.


### cluster:
A cluster is when multiple nodes (computers, devices connected to the network) are linked together to perform one task. 


**Benefits**
- If one server shutdowns another one is active to replace it.
- Can be used for smaller, or larger networks depending on the amount of devices connected.


**Resource Implications**
Clients access the networks one, or more, servers to direct traffic around the network.


**Communications**
Mssages can be sent between PC's via the network.


### centralised
With this network there is a central server that all users will connect to. This server will store the information that you provide to them, aswell as any communication you've had.


**Resource Implications**
Clients are required aswell as the main server which contains information, and communication.


**Communications**
The main server saves communication made between computers. This allows companies to check for potentially harmful material.


**Working practice**
There is always a risk of information leakage. But with communication being monitered that risk is lessened, and may be tracked.


**Information sharing**
Information passing through the main server is stored. This can be reviewed in the future.


### virtualised 
- External virtulisation is the when multiple networks are connected together to form a virtual unit. 
- Internal virtulisation is when a simulated network is given to a container on a network. 


**Resource Implications**
Using a router, connect to the cloud network.


**Communications**
Communication is made easy because you have an established platform when working in a group. Files may be shared, updated, and freely edited depending on settings. 

**EInformation Sharing**
As long as you have a compatible device, it doesnt matter where you are, you will be able to share information with others. This is invaluable when working with a group.


# IEEE
Electrical & Electronics Engineers (IEEE)
### IEEE 802.3
IEEE 802.3 is the access control for media, and the physical layer. 

### IEEE 802.7
IEEE 802.7 is used for broadband local area networks. Testing, design and installation are the priorities with this broadband cable.

### IEEE 802.8
IEEE 802.8 is used mostly with fibre optic developments. This IEEE is used to test fibre optic used with local area networks.

### IEEE 802.11
IEEE 802.11 uses frequency bands to implement wireless local area network computer communication.

# Routed protocols
Router protocols are what give a router the ability to communicate, with another router. The routers have to exchange information to make the link. The most popular routing protocol is IP addresses.

# IPv4
Internet protocol version 4 (IPv4) used to be an essential protocol. Although later became obsolete due to the volume of users, it was running out of IP adresses. To remedy the problem IPv6 was created which has 340,282,366,920,938,463,463,374,607,431,768,211,456 addresses.

# Global unicast
Global unicast is a feature of IPv6 which gives you a globally unique address. It gives a convenient, publically route that can be accessed via the internet, or public domain. Although there is a risk of security breaches due to packet loss.

# the impact of network topology, communication and bandwidth requirements
### logical
The logical topology arranges nodes on a network, and defines their communication. Logical topology governs how signals, and data pass through the network and how that's handled on the devices connected to the network. 

One type of logical topology is Ethernet. Ethernet is the most used local area network technology. Ethernet formats how data is transmitted to other network devices on the same network.

### physical
Physical topology is physical hardware for a network. This includes clients and servers on the network, and any asociated cables. It's important to have structure when using cables, so that they dont become tangled.

# Types of Physical Topologies
### Star
The star topology is where all devices, and clients, are connected to one central node. This would mainly be a hub or switch.

### Ring
The ring topology is where the clients, and devices, on the network are connected in a circle layout.

### Bus
The bus topology is where the clients, and devices, are connected on a single line. The line is terminated on both ends.

### The Difference Between Physical and Logical 
Logical is designing and building the network. Whereas physical is setting up the real world equipment.

# The interdependence of workstation hardware


### Client Software
Client software works within local area network, and wide area networks. It acts like an interface between a client’s computer, and the server on the network. The client software is located on the client’s computer. Client software can be word processors, Web browsers or any other service that the computer provides.

### Server Software
Server software is used with network servers. The software provides the server with the function to interact with the clients, and device on the network.

### Client Operating System
Client operating system is a low-level software that supports a computer's basic functions. 

### Server Operating system
The Server operating system is designed for server’s functions and objectives. These functions include communicating with clients and other devices. It also allows you to manage your database, web mail and files.

### Firewall
The firewall filters traffic entering the network, and will filter out most harmful software/packets of data.

### Proxies
Proxies act as a halfway point between a server, and will take requests from the client. The client will give the proxy server requests.

# Comparison of network and Cabling
### Network Comparison
A network card allows a computer to connect to a network. The card faciliatates the exchange of data and information between the network and the client's PC. Another method of connection to a network would be the use of a wireless network. This wireless network allows the connection of two networks, without the need for a wired connection. This means that the network can be accessed from anywhere, via the internet. Another network connection would be mobile network connection. A mobile network distributes cells which each have a fixed transceiver, or base station.

### Cabling Used
Cabling is used to connect devices and hardware together for the purpose of transmitting data between. Below are various cables that can be used when setting up a network.

### Patch Cables
Patch cables are used to connect electrical devices together. They are commonly used for signal routing, and connecting devices that share a network.

### Shielded Cables
A shielded cable is used to transmit data from one device to another. This cable has a shield layer which comprises of braided stands of copper. Shieldled cabling reduces electrical noise that adversly effects the signals that are transmitted.

### Twisted pair
Twisted pair cabling contains twisted wires which reduce the chance of crosstalk. It also helps fight electromagnetic interference between the data, and packets being transported.

### Permissions
Permissions are network privileges that apply to clients, and devices on your network. A client may not have access to admin permissions for example. Below are various permissions.

### NTFS
NTFS permissions allow access to certain files and folders on a network. You can setup who has access to read, and or write on said files. NTFS allows the right users, the permissions they need to maintain the network, and the files on it.

### Shared Permissions
Shared permissions allow set privaledges for shared files. The files would then be restricted to those who aren't on the network.

### Local Workstation Architecture
Workstation Architecture is designed for technical or scientific applications. It is intended to be used by a network with one user. This workstation is mainly used to manage local area networks. Local workstations are used to maintain networks, and to potentially fix problems that occur.

### System Bus
A system bus creates a path for data to travel to the main memory of the computer, and then carried to the microprocessor. It establishes a communication pathway for the data to travel on.

# Network design
I'll start by creating my star network. A star network is where multiple devices are connected to a central point. I need to include multiple devices: 3 pc's, a server, a switch, a primer and an access point. My central point in my star network was the hub. I needed to be able to communicate with other devices on the network. 

![](https://i.imgur.com/vnKPN9X.png)

### Set Configurations
#### Network 1

PC1 192.168.1.100 PC2 192.168.1.101 PC3 192.168.1.102

Server 192.168.1.10

Router 192.168.1.1

#### Network 2

PC1 192.168.10.100 PC2 192.168.10.101 PC3 192.168.10.102

Server 192.168.10.10

Router 192.168.10.1

# Creating the Network








