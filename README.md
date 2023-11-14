# TCP-IP

TCP / IP stands for transmission control protocol / internet protocol.

The protocol is used in 
all parts of the Internet to enable different devices to communicate. 
The protocol is formed from four distinct layers that form the TCP / IP stack. These layers 
are application, transport, network, link and each is responsible for a seperate part of 
communication over the Internet. 

![image](https://github.com/Minwauu/TCP-IP/assets/110039102/99d462b7-3f11-4239-bb95-f38d0bf3f2df)
![image](https://github.com/Minwauu/TCP-IP/assets/110039102/6cbd190a-fc4d-4ad2-a819-40bc02ea42bc)

Once a packet has been received by its intended recipient, it is stripped of its extra 
information by reversing the TCP / IP stack. 

Firstly, the link layer removes MAC addresses from the packet. Next, the network layer 
removes IP addresses before the transport layer uses the packet’s port number to 
determine the correct application to send the packet to. The transport layer also uses the 
packet’s sequence number to ensure that it is in the correct position relative to other 
packets in the same transmission. 

Finally, the application layer receives the packets and displays the information to the user 
accordingly. 



![image](https://github.com/Minwauu/TCP-IP/assets/110039102/32a90a81-61b6-4390-b73d-8679ed4cefac)

