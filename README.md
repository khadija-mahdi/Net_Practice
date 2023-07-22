# Net_Practice

### ***What is networking :***

- ***computer network  :***
    
    *In simple terms, networking is the process of connecting computers and other devices together so they can communicate and share information. It's like creating a system of highways or roads that allow data to travel between devices. Networking enables devices to share resources like files, printers, and internet connections, and it makes communication and collaboration between devices and people easier. It can be done using cables or wirelessly, and it's what makes the internet and other networks work.*
    
    A computer network is made up of two or more computers that are linked together via connectors (wired) or wireless connections for the goal of sending information, communicating, or ability to share resources and information. A computer network is built with hardware (such as gateways, switches, access points, and cables) and software (e.g., operating systems or business applications).
    
    A computer network is typically described by its geographical region. A LAN (local area network), for example, connects computers within the same particular physical space, such as an office building, while a WAN (wide area network) connects computers across continents. The internet is the most visible example of a WAN, designed to connect huge amounts of devices around the world.
    
    ***`Uses of Computer Networks`***
    
    - Communicating using email, video, instant messaging, etc.
    - Sharing devices such as printers, scanners, etc.
    - Sharing software and operating programs on remote systems.
    - Allowing network users to easily access and maintain information.
    - Sharing files.
    
    **`Network devices`**
    
    - ***Host :***
        
        *are any device which sends or receive traffic : computer , laptop , severs, cloud server, internet of things..* 
        
        - Client : initiate requests
            
            —> relative to specific communication
            
        - Servers : respond the requests, and the server are simply computers with software installed  which responds to specific requests.
    - ***Repeater :***
        
         *is a device that takes a weak signal and makes it stronger so that it can travel a longer distance without losing quality.* 
        
    - ***Hub :***
        
        Think of a hub as a meeting point where devices gather to communicate with each other. When one device wants to send data to another device, it sends it to the hub. The hub then broadcasts the data to all the other devices connected to it. It's like a speaker in the middle of a room, shouting out a message to everyone present. However, the hub doesn't have the ability to understand or manage the data—it simply passes it along to all devices.
        
        <aside>
        💡 `hubs are multi-port Repeaters.                                     facilitates scaling communication between additional hosts          everyone receives everyone else’s data.`
        
        </aside>
        
    - ***Router :***
        
        is a device that connects different devices in a network and helps them communicate with each other. It directs data between devices and ensures that information gets to the right destination efficiently. Think of it as a traffic cop for data on the internet or a local network, directing the flow of information so devices can talk to each other.
        
    - ***Switch :***
        
        is a device that connects computers and other devices within a local network. It helps them talk to each other directly and efficiently by sending data only to the intended recipient, making network communication faster and more organized.
        
    
      ******
    
    <aside>
    💡 The differences between a router and a switch:
    
    - A router connects different networks together and helps data travel between them. It operates at a higher level and handles traffic between networks.
    - A switch connects devices within a single network and facilitates communication between devices on that network. It operates at a lower level and forwards data directly to the intended recipient within the same network
    </aside>
    

### ***Types of networking:***

![Network.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Network.png)

- ***Personal Area Network (PAN) :***
    
    *A Personal Area Network (PAN) is a type of computer network that connects devices within a relatively small area, typically within a person's workspace or living space. This usually involves connecting devices like laptops, smartphones, and other personal devices to each other wirelessly using technologies like Bluetooth or infrared. PANs are designed to provide a convenient way for individuals to connect and share information between their personal devices without the need for a larger network infrastructure.*
    
    USB , Bluetoth … (1 —> 10 m) 
    
    ![very-short--questions---1---teachoo.jpeg](Net_Practice%200779614fb84b4221a06a21db125ed4a4/very-short--questions---1---teachoo.jpeg)
    
- ****Local Area Network (LAN) :****
    
    A Local Area Network (LAN) connects computers and devices within a relatively small area, such as an office building or home. LANs are typically used for sharing resources like printers and files, as well as for communication and collaboration between devices. They are usually faster and more secure than wide area networks (WANs) because they cover a smaller area.
    
    Home, Office, School (10m ——>  1k);
    
    ![basic-home-lan.jpeg](Net_Practice%200779614fb84b4221a06a21db125ed4a4/basic-home-lan.jpeg)
    
- *****Campus Area Network (CAN) :*****
    
    A Campus Area Network (CAN) is a type of computer network that connects devices within a limited geographical area, such as a university campus or corporate campus. CANs are designed to provide high-speed connections between buildings and other areas within the campus network, allowing for easy communication and collaboration between devices. They are typically faster and more secure than wide area networks (WANs) because they cover a smaller area.
    
    ![mang-can-1.jpeg](Net_Practice%200779614fb84b4221a06a21db125ed4a4/mang-can-1.jpeg)
    
- ****Metropolitan Area Network (MAN) :****
    
    A Metropolitan Area Network (MAN) is a type of computer network that covers a larger geographical area than a local area network (LAN) but a smaller area than a wide area network (WAN). MANs are typically used to connect devices and computers in a city or metropolitan area, providing high-speed connections for communication and collaboration between devices. They are usually faster and more secure than WANs because they cover a smaller area.
    
    ![download.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/download.png)
    
- ****Wide Area Network (WAN) :****
    
    A wide area network (WAN) is a large computer network that connects groups of computers over large distances. WANs are often used by large businesses to connect their office networks; each office typically has its own local area network, or LAN ,and these LANs connect via a WAN. These long connections may be formed in several different ways, including leased lines, [VPNs](https://www.cloudflare.com/learning/access-management/what-is-a-vpn/), or IP tunnels
    
    ![Wide-area-network-WAN-diagram-1024x911.jpeg](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Wide-area-network-WAN-diagram-1024x911.jpeg)
    

### ***The OSI Model (Open Systems Interconnection) :***

![1642021669943.jpeg](Net_Practice%200779614fb84b4221a06a21db125ed4a4/1642021669943.jpeg)

- ***Open Systems Interconnection model :***
    
     is a conceptual framework that helps us understand how network communication happens between different devices in a computer network. It divides the entire process into seven layers, each responsible for specific tasks.
    
- ***what is layer :***
    
    ***a layer in the context of the OSI model refers to a specific level or stage within the framework of network communication. Think of it as a distinct piece of functionality or responsibility that contributes to the overall process of transmitting data between devices.***
    
    ***Each layer has a specific role and performs certain tasks to ensure that data is properly transmitted, received, and understood by the devices involved in the communication. These layers work together in a hierarchical manner, with each layer building upon the services provided by the layer below it.***
    
    ***By dividing the network communication process into different layers, the OSI model allows for easier understanding, troubleshooting, and standardization of network protocols and technologies. It helps ensure that different devices and systems can communicate effectively, even if they are from different manufacturers or use different underlying technologies.***
    
    ### `***Here's a simplified explanation of each layer:***`
    
    1. ***Physical Layer :**  This is the lowest layer and deals with the actual physical transmission of data through cables, wires, or wireless signals.*
    2. **Data Link Layer** *: This layer focuses on organizing raw data into frames or packets and provides error detection and correction to ensure reliable transmission.*
    3. ***Network Layer** : The network layer handles the addressing and routing of data packets across different networks. It determines the best path for data to travel from the source to the destination.*
    4. **Transport Laye***r  :   This layer ensures reliable end-to-end communication by segmenting data from the upper layers into smaller units, managing data sequencing, and providing error recovery.*
    5. ***Session Layer**   : The session layer establishes, manages, and terminates communication sessions between applications. It handles session synchronization and allows for checkpointing and recovery.*
    6. ***Presentation Layer** : This layer is responsible for data representation, encryption, and compression. It ensures that data from the application layer is properly formatted and understandable by the receiving device.*
    7. ***Application Layer**  : The application layer is the closest to the end-user and provides network services directly to applications. It enables user interaction and implements protocols for specific applications like email, web browsing, file transfer, etc.*
    

### **TCP/IP Model (the Transmission Control Protocol / the Internet Protocol ):**

![2335a085-5678-472d-8bf6-509f073cce6c.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/2335a085-5678-472d-8bf6-509f073cce6c.png)

***Deferent between TCP (Transmission Control Protocol) and IP (Internet Protocol) :*** 

*TCP / IP : are both integral components of the TCP/IP protocol suite, which is the set of protocols used for communication on the Internet and most computer networks.*

- ***TCP (Transmission Control Protocol):***
    - TCP is a connection-oriented protocol that provides reliable, ordered, and error-checked delivery of data packets between devices.
    - It ensures that data sent from one device reaches its destination without loss or corruption.
    - TCP achieves reliability through mechanisms such as acknowledgment of received packets, retransmission of lost packets, and flow control to prevent overwhelming the receiver.
    - TCP establishes a connection between the sender and receiver before data transmission and ensures that packets are received in the correct order.
    - It is commonly used for applications that require guaranteed delivery and accurate sequencing of data, such as web browsing, file transfer, and email.
    
- ***IP (Internet Protocol):**  is the identity of each host .*
    
    IP addresses are 32 bits . represented as four Octets, each octet can be [0,255];
    
    - IP is a connectionless protocol responsible for the addressing and routing of data packets in a network.
    - It assigns unique IP addresses to devices on a network, allowing them to be identified and located.
    - IP routes data packets across interconnected networks, determining the best path for packets to reach their intended destinations.
    - It is a best-effort delivery protocol, meaning it does not guarantee reliable or ordered delivery of packets.
    - IP operates at a lower level than TCP and is considered the foundation of network communication, handling the basic transmission and routing of data.

<aside>
💡 like you need phone number to send or reserve calls , or mail address to send or reserve mails , you need ip address to send or reserve packet .

</aside>

In summary, TCP provides reliability, sequencing, and flow control for data transmission, ensuring accurate delivery of information between devices. IP, on the other hand, focuses on addressing and routing, determining how data packets move across networks. TCP and IP work together in the TCP/IP suite, with TCP relying on IP for packet delivery and routing

- ***IPv4 & IPv6***
    
    > *IPv4 is the fourth edition of the Internet Protocol and is the first Internet protocol used worldwide. IPv4 is a protocol for exchanging data over packet-switched networks. There is no guarantee that data will be delivered correctly, and there is the possibility of delivering duplicate packets or delivering the packets out of order. Accurate and sequential delivery of data is guaranteed by the higher protocol, TCP (and to some extent by UDP).*
    > 
    
    > *A class*
    > 
    > 
    > *Class A is the highest class and has an IP address ranging from 1 to 126 (0, 127 reserved). The three numbers of the second, third and fourth units are IPs that A Class can freely assign to network users.*
    > 
    > ### *B class*
    > 
    > *Class B is the second highest unit class, and in the IP configuration, the three numbers of the first unit have one of 128 - 191, and the three numbers of the second unit indicate the network that B Class can access.*
    > 
    > ### *C class*
    > 
    > *C Class is the lowest class, and in the IP configuration, the three numbers of the first unit have one of 192 -223, and the three numbers of the second and third units indicate the network that C Class can access. The IPs that C Class can freely assign are 254 of the last fourth unit.*
    > 
    > > *IPv6 (IP version 6) is the latest generation Internet Protocol IP defined by the Internet Engineering Task Force (IETF). The first stable IP version was IPv4. IPv6 is meant to eventually replace IPv4, but the two are now intertwined and most engineers are doing both together.*
    > > 
    > 
    

- ***What is a subnet?***
    
    *A subnet or a subnetwork is a network inside a network. Subnets make networks more efficient.*
    
    *Subnetting is the process of stealing bits from the HOST part of IP address in order to divide the large network into smaller ones called subnets. After subnetting, we end up with NETWORK SUBNET HOST fields, and we always reserve an IP address to identify the subnet and another one to identify the broadcast subnet address, and through subnetting, network traffic can travel a shorter distance without passing through unnecessary routes to reach its destination.*
    
    The network-mask, subnet-mask or in our project only called mask is there to decide which range of ip address are part of the same subnet.
    
    There are 2 different ways of writing the mask:
    
    - "Dot-decimal notation": `255.255.255.0`
    - "Class Inter-Domain Routing" or "CIDR": `/24`
    
    The more usable ip-addresses you need in one subnet, the less subnets you will be able to create.
    
    To help you understanding it, I found this table very helpful:
    
    | CIDR | Dot-decimal | Number of IP addresses per subnet | Usable IP addresses per subnet | Number of subnets |
    | --- | --- | --- | --- | --- |
    | /32 | 255.255.255.255 | 1 | 0 | 256 |
    | /31 | 255.255.255.254 | 2 | 0 | 128 |
    | /30 | 255.255.255.252 | 4 | 2 | 64 |
    | /29 | 255.255.255.248 | 8 | 6 | 32 |
    | /28 | 255.255.255.240 | 16 | 14 | 16 |
    | /27 | 255.255.255.224 | 32 | 30 | 8 |
    | /26 | 255.255.255.192 | 64 | 62 | 4 |
    | /25 | 255.255.255.128 | 128 | 126 | 2 |
    | /24 | 255.255.255.0 | 256 | 254 | 1 |
    
    The number of usable IP-addresses per subnet is lower than the total number of IP's because the first address is reserved as the network-address of the subnet and the last address is reserved as a broadcast addresses**.**
    
    i.e. for mask `255.255.255.252`:
    
    network: `190.3.2.252`
    
    broadcast: `190.3.2.255`
    
    usable IP's: `190.3.2.253`, `190.3.2.254`
    

### Subnet Mask

A subnet mask is information for dividing a network address and a host address. By aligning the IP address and subnet mask together, you can separate the network and host parts of the address.

```
11000000.10101000.01111011.10000100 - IPaddress (192.168.123.132)
11111111.11111111.11111111.00000000 - mask (255.255.255.0)
						|
                        v
11000000.10101000.01111011.00000000 -IP address (192.168.123.0)
00000000.00000000.00000000.10000100 - mask (000.000.000.132)
```

To put it simply, the part represented by 1 in the subnet mask is used as the network address, and the part represented by 0 is used as the host address.

- $***LEVELS :***$
    
    
    - $***LEVEL_1:***$
        
        > *Goal 1. My PC must be connected to my brother's computer.*
        > 
        
        > *In order for these two computers to communicate, both computers must be on the same LAN.*
        > 
        
        > *Since the mask (subnet mask) of the two computers is currently specified, you can write your answer based on the concept of network address/host address*
        > 
        
        ![Level_1.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_1.png)
        
        The solution will be anything in the range of **104.96.23.0 - 104.96.23.255**
        
        - **211.191.0.0:** Represents the network address.
        - **211.191.255.255:** Represents the broadcast address.
        - **211.191.89.75:** Already taken by host *Client C*.
    - $***LEVEL_2:***$
        
        This is the same problem as level 1.
        
        The difference is that Mask contains numbers in an unfamiliar format.
        
        Masks marked with /30 mean:
        
        ```
        /30 = 11111111.11111111.11111111.11111100
        ```
        
        That is, how many consecutive 1s are there in the subnet mask characteristic where 1s must appear consecutively.
        
        ![Level_2.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_2.png)
        
        A1 : The answer is in the range of: 192.168.20.192 - 192.168.20.223
        
        B1 : Since *Client B* is on the same private network as *Client A*, they should have the exact same subnet mask.
        
        D1 and  C1 : *255.255.255.252 =⇒ \30* 
        
        The answers can then be any addresses, as long as they meet the following conditions:
        
        - The network address (first 30 bits) must be identical for *Client D* and *Client C*.
        - The host bits (last 2 bits) cannot be all 1, nor all 0.
        - *Client D* and *Client C* do not have identical IP addresses.
        
    - $***LEVEL_3:***$
        
        This is the first level where the switch appears. However, we know that even if there is a switch, it is within the same network that only the IP and subnet mask need to be entered.
        
        ![Level_3.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_3.png)
        
        SO the B1 AND C1 ABD A1 must all have the same subnet mask .
        
        The solution will be anything in the range of `104.198.241.0 - 104.198.241.128` Excluding of course the network address and the broadcast address.
        
    - $***LEVEL_4:***$
        
        This is the first level where the router appears.
        
        A router
        
        **must have a different network address for each interface.**
        
        Enter the router's network address so that the interface connected to the switch has the same network address without overlapping.
        
        ![Level_4.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_4.png)
        
        Since none of the masks on *Interface B1*, *Interface A1*, and *Interface R1* are entered, we are free to chose our own subnet mask.
        
    - $***LEVEL_5:***$
        
        
        This is the level where network communication using a router first appears.
        
        Static routing using route tables is also the first to appear.
        
        Static routing is a method in which an administrator directly specifies a route to a specific network. If the target to be sent matches the left side of the table, the message is requested to be forwarded to the right side.
        
        The default in the example is equal to 0.0.0.0/0, which matches everything.
        
        ![Level_5.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_5.png)
        
        It's good to understand it in the same way.
        
        In goal 3 of this level, A wants to communicate with B, so after setting the destination B's network to be included, enter the IP of the router connected to the right.
        
        ![https://velog.velcdn.com/images/mseo/post/64e7aaf8-66a2-4623-9b68-b01ff314881a/image.png](https://velog.velcdn.com/images/mseo/post/64e7aaf8-66a2-4623-9b68-b01ff314881a/image.png)
        
        However, this number is not the only answer. For example, you can put a default value in order to send anything you want to send, such as a table in B.
        
        ![https://velog.velcdn.com/images/mseo/post/16cb36f0-8238-44d4-99eb-64ab390c1942/image.png](https://velog.velcdn.com/images/mseo/post/16cb36f0-8238-44d4-99eb-64ab390c1942/image.png)
        
        Or, even if the subnet mask is different, it is possible if the IP of the destination is included.
        
        ![https://velog.velcdn.com/images/mseo/post/b05026cc-c7f1-40e4-81ce-b718bf3d30d4/image.png](https://velog.velcdn.com/images/mseo/post/b05026cc-c7f1-40e4-81ce-b718bf3d30d4/image.png)
        
    - $***LEVEL_6:***$
        
        This is the level where the Internet first appears. But you needn't be afraid.
        
        You can break it with enough knowledge from above.
        
        If you fill in the parts that can be filled with other knowledge first, the problematic part will be the routing tables on the Internet.
        
        If you put in a value like defalut to end it easily, you'll get a KO.
        
        The reason is that interfaces of other nets and client A cannot be distinguished by putting the default value.
        
        The easiest answer to distinguish between the two is to put the network address value of client A in the routing table. For example, an answer like **45.80.114.129/25 .**
        
        However, this number is not the only answer.
        
        ![Level_6.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_6.png)
        
        The **next hop** of the internet is already entered, and matches the IP address of the
        
        *Interface R2 ,*Therefore we only need to bother with the destination of the internet.
        
        The internet must send its packets to *Client A* . To do so, the internet's destination must match the network address of *Client A ,* Let's find the network address of *Client A Client A* 's mask is : *255.255.255.128*
        
        so the range : 29*.64.6.127 -* 29*.64.6.254*
        
    - $***LEVEL_7:***$
        
        This is the first level where several routers appear.
        
        The goal of this level is to configure the two computers to communicate with each other using two routers.
        
        From our previous knowledge, we know that R11 and A1 are the same network, R22 and C1 are the same network, and R12 and R21 are the same network.
        
        At the same time, each of these three networks must be a different network.
        
        This is because routers look at the address of the destination and distinguish whether it is a local network or not, and if both are not distinguished while passing through two routers, proper communication will not be possible.
        
        Therefore, the subnet mask must be set to distinguish between R11-A1 and R12-R21 with clues. In the case of R22-C1, it is better to put a completely different network address.
        
        ![https://velog.velcdn.com/images/mseo/post/2b59c759-bc29-41cb-93c2-769b684ac750/image.png](https://velog.velcdn.com/images/mseo/post/2b59c759-bc29-41cb-93c2-769b684ac750/image.png)
        
    - $***LEVEL_8:***$
        
        This is the level where the routing table is doubled, and all clients must be connected to the Internet.
        
        First of all, since the range where communication with the Internet is possible is specified, you can see that the IP addresses of C1 and D1 are within 131.241.182.0/26. (131.241.182.1 to 62)
        
        We also know that R21, R22, and R23 must be different network addresses.
        
        Based on the above reasons and the specified values, you can set the IP by dividing it.
        
        ![https://velog.velcdn.com/images/mseo/post/9bbf692e-784a-488c-aa22-90fb4e532ac9/image.png](https://velog.velcdn.com/images/mseo/post/9bbf692e-784a-488c-aa22-90fb4e532ac9/image.png)
        
    - $***LEVEL_9:***$
        
        This is a hybrid problem from the previous levels.
        
        However, you only need to set the exact same network addresses and addresses of different networks, and put them in the routing table so that they can communicate.
        
        **The same network in this problem is:**
        
        1) B1-A1-R11
        
        2) R13-R21
        
        3) R22-C1
        
        4) R23-D1
        
        **Also, on a per-router basis, their network addresses must be differentiated.**
        
        1) R21 != R22 != R23
        
        2) R11 != R12 != R13
        
        **Lastly, the IP connected to the Internet must not be a private IP.**
        
        ![Level_9.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_9.png)
        
    - $***LEVEL_10:***$
        
        It is a problem in the form of level 8 + 9, in which the routing table of the Internet is reduced to one in level 9.
        
        If you have learned well by solving the existing problems, the explanation of additional answers will be skipped because it is a problem that can be easily solved because there are many clues.
        
        If communication does not work after filling in the parts that can be filled through clues, you need to check if there is a part where the subnet mask is set so that it can be recognized as the same network.
        
        ![Level_10.png](Net_Practice%200779614fb84b4221a06a21db125ed4a4/Level_10.png)