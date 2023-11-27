## Mj's Reading Notes 

## Reading notes 2
Understanding ports is a way to understand how your network works. 

1. What is a port? Describe it with an analogy that would help a family member understand. A port is a specific virtual location that allows packet traffic. It is like a interstate with as many lanes as there are ports open. Each car can only go to the end and start destination and is carrying data that is important for both destinations.
2. What does a port scanner send to a port to check the current status? It sends a TCP or UDP network packet and waits for the status.
3. When a port scanner sends a request to connect, what are the three possible responses? Describe them. Open, Accepted - Computer asks what it can do for us. Closed, Not listening - computer says port is in use and unavailable. Filtered, Dropped, Blocked - Computer doesn't respond. 
4. What is the difference between TCP and UDP? TCP stands for Transmission Control Protocol and confirms that each packet transmission is successful. UDP stands for User datagram protocol and just sends packets without confirming anything.
---
1. List and describe the ports used for the following:
- Telnet - 23 - connects a remote device to a console screen and view info on the single terminal screen. 
- SSH - 22 - Secure shell connects to and sends information with encryption. similar to Telnet but more secure.
- DNS - 53 - The Domain name system searches and returns the name we type in to the IP address assosciated with it.
- SMTP - 25 - Simple mail transfer protocol is a common port for email traffic between devices.
- HTTP - 80 - Web Server communication.
- HTTPS - 443 - Encrypted Web Server communicaiton.
- RDP - 3389 - Remote Desktop Protocol provides remote access view of a remote desktop.
- Ping - Ping does not use a specified port. 

### I got my information from these sites 
- [What is a Port Scanner and How Does it Work?](https://www.varonis.com/blog/port-scanning-techniques)
- [Common Ports](https://www.professormesser.com/network-plus/n10-008/n10-008-video/common-ports-n10-008/)

## Things I want to know more about 