### Intro to Networking..
Networking, also known as computer networking, is the practice of transporting and exchanging data between nodes over a shared medium in an information system. Networking comprises not only the design, construction and use of a network, but also the management, maintenance and operation of the network infrastructure, software and policies.

Computer networking enables devices and endpoints to be connected to each other on a local area network (LAN) or to a larger network, such as the internet or a private wide area network (WAN). This is an essential function for service providers, businesses and consumers worldwide to share resources, use or offer services, and communicate. Networking facilitates everything from telephone calls to text messaging to streaming video to the internet of things (IoT).
### Components of networking
Computer networking requires the use of physical network infrastructure -- including switches, routers and wireless access points -- and the underlying firmware that operates such equipment. Other components include the software necessary to monitor, manage and secure the network.

Additionally, networks rely on the use of standard protocols to uniformly perform discrete functions or communicate different types of data, regardless of the underlying hardware.

For example, voice over IP (VoIP) can transport IP telephony traffic to any endpoint that supports the protocol. HTTP provides a common way for browsers to display webpages. The internet protocol suite, also known as TCP/IP, is a family of protocols responsible for transporting data and services over an IP-based network.
### Why NetPractice
NetPractice is a project made to make you understand IPV4 addressing and subnetting.

IP stands for internet protocol and it means the protocol used to connect between computers.

An ip4v is a 32 bit value that is divided to 4 sub values meaning that we will have 4294967295 address.
### IP Addresses
An IP address, short for Internet Protocol address, is a unique numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. IP addresses serve two primary functions: identifying the host or network interface and providing the location of the host in the network.

IP addresses are fundamental to the operation of the Internet and are essential for devices to communicate with each other. When you connect to the internet, your Internet Service Provider (ISP) assigns your device an IP address. This address allows other devices on the internet to identify and communicate with your device.

IPv4 (Internet Protocol version 4): IPv4 addresses are 32-bit numerical addresses written in the format of four sets of numbers separated by periods (for example, 192.168.1.1). IPv4 addresses were the first version of IP addresses and are still widely used today, although the available address space is running out due to the increasing number of devices connected to the internet.

IP addresses enable devices to send and receive data packets, facilitating activities such as browsing the web, sending emails, and accessing various online services. They are a crucial part of how information is exchanged on the internet.
### Switch device
A network switch is a device used in computer networking to connect devices together on a computer network and uses packet switching to forward data to its destination. Unlike network hubs, which broadcast data to all devices in a network, switches only send data to the specific device that needs it, making them more efficient in terms of bandwidth usage.

In summary, a network switch is a fundamental networking device that efficiently connects multiple devices within a local area network (LAN). Its ability to forward data only to the devices that need it, based on MAC addresses, makes it a vital component in modern computer networking.
### Router device
A router is a network device that forwards data packets between computer networks. Routers operate at the third layer (Network Layer) of the OSI model and use IP addresses to determine the best path for forwarding the packets.

### Subnetting
Subnetting is the process to take a network and dividing it to small chunks of other networks.
This solves the problem of unused its within a network.

   Example here we have 2 networks:
   
→First is 10.0.0.0/25

→Second is 10.0.0.128/25


### Classless addressing
A ip class gives us too much possible address even a class C address gives us 255 dress when we want a network with only 2 or 3 hosts, to solve this we start using smaller masks to limit the range of a specific network.

