# The OSI Layers 


### Layer 1 - Physical
The physical layer is literally reponsible for physically transmitting information. This layer sends information in the most rootamentary form of a bit (0's and 1's).

### Layer 2 - Data Link 
This layer is responsible for getting the right information to the right source - node to node transmission. It is paramount that this layer eliminate as many errors as possible! The Data Link Layer delivers packets based on the MAC address of the host. The DLL gains this MAC address by sending an Address Resolution Protocol to all the possible hosts - and the host with the corresponding IP address in the ARP will respond with it's MAC address. 

Additionally, DLL adds the sender and receivers MAC addresses into the header of the packet!

### Layer 3 - Network 
The Network layer ensures safe travels for the packet to different networks while choosing the fastest route for the packet. It also adds the Sender and Receiver's address into the Header of the packet. 

### Layer 4 - Transport
Arguably one of the most complex, and important, layers of the OSI Model. The Transport is responsible for the delivery of the data as well as acknowledgement of successful transmission and initiaing a re-transmission in the event of an error. When sending data, the Transport layer assigns Sending and Receiving Port Numbers to the header and the receiving node reassembles the transmitted data and pushes it to the proper channel. 

### Layer 5 - Session 
The Session layer creates connections, uncomplex maintenance, network authentication, security, and termination of connections. 

### Layer 6 - Presentation 
The presentation layer takes data and prepares it to be transmitted. It does so by translating different data to different forms, removing excess and unnecessary bits, and encrypting or de-encrypting data. 

### Layer 7 - Application 
The application layer is simply the source producing data that requires transportation. 


# OSI Layer Examples


### Layer 1 - Physical
1. Bit Synchronization 
2. Bit Rate Control
### Layer 2 - Data Link 
1. Framing
2. Error Control
3. Flow Control
### Layer 3 - Network 
1. Routing
### Layer 4 - Transport
1. Connection-Oriented Service
2. Connectionless Service
### Layer 5 - Session 
1. Synchronization 
2. Controls Dialogue
### Layer 6 - Presentation 
See original description!
### Layer 7 - Application 
1. E-Mail
2. Web Browsers