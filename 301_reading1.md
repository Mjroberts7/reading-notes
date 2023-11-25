# Mj's Reading notes
## 301 
## Reading notes 1
learning about OSI and wireshark will help me gain experience with tools and concepts that network professionals use often. 

1. What does “OSI” stand for? OSI standsfor Open Systems Interconnection
2. List the 7 layers of the OSI model and what each one is responsible for. 
- a. The Physical layer is the connection between devices transmitting bits. 
- The Data link layer is responsible for making sure the data is error-free over the physical layer. 
- The Network layer transmits the data from source to the destination using the shortest path possible and places the IP addresses in a header. 
- The Transport layer delivers the complete message using data as Segments. It configures the port numbers in the header and sends that with the segmented data to the Network layer. 
- The Session layer is responsible for establishing the connection, maintenance, authentication, and security of the sessions.
-  The Presentation layer or Translation layer is exactly what it sounds like. Translates the data to the required format.
- The Application layer is the final layer and has four main functions. It allows the user to log on to a remote host. Allows file access and management. Provide email service. As well as provides database sources with access to global information.  
3. Distinguish which layers are the “hardware layers”, and which layers are the “software layers."  What does that even mean?  The first four layers are the hardware layers (Physical, DLL, Network, and Transport). The last three layers are the software layers (Session, Presentation, and Application). The difference is basically saying the data in each of these sections is primarily manipulated through whichever avenue they belong in. As in the software layers are presented through the software, and the data is being manipulated during the hardware layers. 
4. How can the OSI model be used in troubleshooting? Understanding the model can help a network expert troubleshoot where exactly in the step the problem is occuring determining if it is a hardware component failure or faulty software configuration. 


1. What is Wireshark? 
2. What is a packet?
3. What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?

i got my information from these sources 
- [Layers of OSI Model](https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/)
- [What Is Wireshark and How Is It Used?](https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it)
## Videos
- [Understanding the OSI Model](https://www.professormesser.com/network-plus/n10-008/n10-008-video/understanding-the-osi-model-3/)
- [Data Communication](https://www.professormesser.com/network-plus/n10-008/n10-008-video/data-communication/)
- [Packet, routers, and reliability](https://www.youtube.com/watch?v=aD_yi5VjF78)


## Things I want to know more about 