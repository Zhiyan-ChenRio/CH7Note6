# Chapter 7 Note
## 7.1,7.2, 7.3, 7.4
  .A network is built by combining a complex network of cables and hardware to share resources. 
  .Cpmputer network is the interconnection of multiple devices, generally termed as Hosts connected using 
  multiple paths for the purpose of sending/receiving data or media.( Ex: Router, Switch, Hub, Bridge)
  .OSI: stands for Open Systems Interconnection. It is a reference model that specifies standards for
  communications protocols and also the functionalities of each layer.(7 layers: Physical; Data Link; Network; Transport;
  Session; Presentation; and Application)
  .Protocol: Protocols, like TCP, IP, UDP, ARP, DHCP, FTP, and others, are sets of rules that determine how entities
  communicate within the OSI model's different layers. 
  .Host name: Each device in the network is associated with a unique device name known as Hostname
  .IP Address (Internet Protocol address): Logical Address, is the network address of the system across the network
  .Classless Inter-Domain Routing (CIDR): A common method to describe networks is Classless Inter-Domain Routing (CIDR);(ex: 
   CIDR address is 192.0.2.0/24)
   .MAC Address (Media Access Control address): Referred to as a physical address, it serves as the distinct identifier f
   or every host and is linked to the NIC (Network Interface Card)
   Port: A port is a digital channel that enables data exchange with various applications on a host, each identified by
   its specific port number
   .Socket: The unique combination of IP address and Port number together are termed as Socket.
   .DNS Server: Domain name system
   .ARP: ARP stands for Address Resolution Protocol
   .RARP: RARP stands for Reverse Address Resolution Protocol
## IP addresses and DNS
   IP addresses are numerical labels assigned to devices on a network, while DNS (Domain Name System) translates human-readable 
   domain names into IP addresses to facilitate internet communication.
## 7.5, 7.6, 7.7
   .IP addresses: Networks and hosts; An IP address is a 32-bit number that uniquely identifies a host (computer or other device,
   such as a printer or router) on a TCP/IP network.
   .Subnet mask: used by the TCP/IP protocol to determine whether a host is on the local subnet or on a remote network
   .Decimal Binary: Internet RFC 1878 (available from InterNIC—Public Information Regarding Internet Domain Name 
   Registration Services) describes the valid subnets and subnet masks that can be used on TCP/IP networks.
   .Network classes: The InterNIC allocates internet addresses, known as IP addresses, which are divided into classes such as A, B, C,
   with each class having its own default subnet mask, while classes D and E are rarely used by regular users.
   .Subnetting: A Class A, B, or C TCP/IP network can be further divided, or subnetted, by a system administrator
   .Default gateways: When a TCP/IP computer wants to communicate with a device on a different network, it decides whether
   to send the data to its default gateway, which connects it to other networks, based on a comparison between the 
   destination IP address and its own subnet
   .Troubleshooting: TCP/IP network problems often stem from errors in configuring subnet masks, IP addresses, or default gateways 
   in a computer's TCP/IP properties, leading to communication issues within local and remote networks
  ## Amazon VPC: 
  Amazon VPC lets you create a customizable, isolated section in the AWS Cloud where you have full control over IP addresses, 
  subnets, routing, and security to launch resources and applications securely
## 7.8, 7.9
  .VPCs and Subnets: A virtual private cloud (VPC) is a virtual network dedicated to your AWS account
  .VPC Geography: A VPC covers all Availability Zones in a region, allowing the creation of subnets within zones
  and optionally in Local Zones for low-latency services, safeguarding against zone failures, with the option to 
  use both IPv4 and IPv6 addressing
  .IP Addressing in your VPC: IP addresses, such as IPv4 for private communication and public IPv4 or IPv6 for 
  internet access, enable communication between resources in your VPC in Amazon EC2 and Amazon VPC
  .Private IPv4 addresses: Private IPv4 addresses, also known as private IPs, are reserved for internal communication within
  your VPC and are not accessible from the public Internet; when you create an instance in your VPC, it's assigned a private
  IP address, and each instance is given a private DNS hostname for resolving its private IP
  .Public IPv4 addresses: Each subnet can be configured to automatically assign a public IPv4 address to the primary network
  interface of any instance launched within it, with the public IP address being linked to the instance's primary private 
  IP address through network address translation (NAT)
  
  
  
