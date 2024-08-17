# DHCP-DNS-WEB_SERVER
!# This project involves configuring two separate networks on different floors to obtain IP addresses from a DHCP server. The goal is to ensure that both networks can access a web server by setting up and integrating DHCP, DNS, and web server services effectively.
 ![image](https://github.com/user-attachments/assets/d475afe5-a954-44c9-bd7a-009c933ee874)




## Click the DHCP server and select services. 

![image](https://github.com/user-attachments/assets/0108acbb-8337-407e-aa37-5125494062c9)











## I am configuring a DHCP server using Packet Tracer. First, I access the DHCP server, open the services tab, and enable the DHCP service. Next, I configure the IP pool, setting aside a static range of 10 IP addresses for servers and printers. Finally, I create a pool of 100 IP addresses to assign to workstations, ensuring that all necessary devices will receive an appropriate IP address.


![image](https://github.com/user-attachments/assets/1da8818f-7b16-40be-a7ea-dbedb556d239)

 











## Now, I am verifying that the DHCP server is working correctly. I go to PC 4, open the IP configuration, and select the DHCP option to obtain an IP address from the DHCP server since both the PC and the server are on the same subnet.

 ![image](https://github.com/user-attachments/assets/1c07b422-2118-40be-9edf-b0ba1a43766e)



## Now that one side of the network is working, I will check the other side. I'll go to PC0 and verify if it can obtain an IP address from the DHCP server as well. This ensures that both networks are properly configured and receiving IP addresses. 
## The other side of the network isn't receiving an IP address from the DHCP server because it’s on a different subnet. I will now check PC0 and review its IP configuration to diagnose the issue. This will help determine if additional configuration, such as a DHCP relay, is needed to ensure devices on different subnets can obtain IP addresses.
 
![image](https://github.com/user-attachments/assets/bd5b7b2b-fc92-4592-8b9b-a58be590ad9a)















## It’s time to configure a DHCP relay on the router to allow devices on the other side of the network to obtain IP addresses from the DHCP server. The DHCP relay will forward DHCP requests from the subnet that isn't directly connected to the DHCP server, enabling devices on different subnets to receive IP addresses.

![image](https://github.com/user-attachments/assets/1e95de6a-230f-4704-b8ed-feb9f5aa4fba)

 











## Now that the DHCP relay is configured, I'll try again to obtain an IP address on PC0. This should allow PC0, which is on a different subnet, to successfully receive an IP address from the DHCP server through the router acting as a relay


 ![image](https://github.com/user-attachments/assets/dddd539b-c3e8-4731-b30d-fc392a691f3c)







## It is working well means the project is working









## I will now go to PC4, open the web browser, and type `www.kulmiye73.com` to check if the web server is functioning properly. This will confirm whether the network and DNS configurations are working, allowing access to the website hosted on the web server.


 
![image](https://github.com/user-attachments/assets/c40f7ef8-44fb-4515-8967-04ca7b68d922)















Now, I'll go to PC0 and open the browser to check if it can access the web server by typing `www.kulmiye73.com`. This will verify whether the network setup and routing are correctly allowing access to the web server from both subnets.
![Uploading image.png…]()

 

# Good job!































