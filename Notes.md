**What is CyberSecurity ?**

Practice of protecting computer networks systems and data from unauthorized access,attacks,damage or theft

**CIA Triads**

**Confidentiality:**

only authorized people can access the data.The data must be secure.
eg:our whatsapp messages should pnly be visible to sender and reciever only 

**Integrity:**

The data should not be altered or tempered with 
eg: if i send 5000 rupees somewhere it should not become 50 thats integrity 

**Availability:**
Systems and data should always be accessible when needed 
eg:atm shoukd work when you need money websites should not crash due to attacks 



/////////////////////////////////////////////////////////////////////////////////

**Types of Cyber threats**

1.Malware 
2.Phishing
3.Ransomware
4.Hacking
5.Denial of Service (DOS)


Types of CyberSecurity

1.NetworkSecuriy
protecting networks from attacks 
eg:Firewalls,  Routers Security

2.Applcation Security
Securing software and apps 
eg:Fixing bugs in website

3.Information Security
Protecting data (files,databases)

4.Cloud Security
Securing data stored online eg: googledrive etc

5.Ethical Hacking
testing systems to find weakness legally



//////////////////////////////////////////////////////////////////////////////////



**What is Computer Networking**

A computer network is a group of devices connected together to share data and communicate 


**Types of Networks**

1.LAN (local area network)
small area network home office
eg: home wifi connecting phone laptop


2.WAN (wide area network)
large area networks covering cities/countries
eg: the internet 

3.MAN(metropolitan area network)
covers a city


IP address

ip address is a unique no assigned to each device 


Routers (The traffic manager)
a router connects different networks and directs traffic
eg: your wifi router at home assigns ip adresses
and sends data to correct addresses

DNS (Domain name system)
converts domain names into ip addresses
eg you type google.com 
dns converts it to ip address

HTTP/HTTPS

HTTP
not secure 
HTTPS 
secured

TCP transfer control protocol 
reliable communication sends data in  form of packets ensures data arrives correctly a little slow if somethings missing sends immediately 

UDP (user datagram protcol)
Fast but less Reliable 
used when fast service is needed  no matter integrity eg streaming gaming


FTP file transfer Protocol
used to transfer files







//////////////////////////////////////////////////////////////////////////////////

 
OSI MODEL 7 layers /  TCP/IP MODELS


Layer 1 — Physical    
TCP/IP: Network Access
This is the bottom layer the actual physical medium carrying the data. Bits become electrical voltages on copper cable, pulses of light in fibre optic cable, or radio waves in Wi-Fi. No addressing happens here — it is purely about transmitting ones and zeros. Everything above depends on this layer working correctly.


Layer 2 — Data Link
TCP/IP: Network Access
This layer handles communication between devices on the same local network (the same Ethernet segment or Wi-Fi network). It wraps packets from Layer 3 into frames and adds physical hardware addresses (MAC addresses) so switches know which port to send a frame out of. While Layer 3 thinks globally (IP addresses, different networks), Layer 2 thinks locally (MAC addresses, same broadcast domain).


Layer 3 — Network
TCP/IP: Internet
This layer handles routing — moving packets from source to destination across multiple different networks. Every device has a logical address (an IP address) at this layer. Routers read these addresses and decide the best path forward, hop by hop, until the packet reaches its destination. This is how data travels from your laptop in Lahore to a server in San Francisco.


Layer 4 — Transport
TCP/IP: Transport
This layer ensures data gets from one application process on one computer to the correct process on another. It breaks large messages into smaller segments, numbers them, and reassembles them at the destination. TCP (Transmission Control Protocol) adds reliability — it checks every piece arrived and re-sends anything lost. UDP (User Datagram Protocol) skips the checks for speed — used in video calls, games, and live streams where a dropped packet is better than a delayed one.


Layer 5 — Session
TCP/IP: Application
A session is an ongoing conversation between two computers. This layer opens that conversation, keeps it alive, and closes it cleanly when done. It also handles re-synchronisation if the connection drops mid-transfer. Think of it like a phone call — someone has to dial, both parties speak, and someone has to hang up.


Layer 6 — Presentation
TCP/IP: Application
This layer acts as a translator between the network and the application. It handles three jobs: encoding (converting data to a format both sides understand), encryption/decryption (scrambling data so only the intended recipient can read it), and compression (shrinking data to save bandwidth). In practice, modern systems fold this into Layer 7.



Layer 7 — Application
TCP/IP: Application
This is the top layer — the one you interact with every day. When you open a browser, send an email, or query a website, data originates here. It is not the application itself (like Chrome), but the rules (protocols) that application uses to communicate over the network.

