## Room Name: What is Networking

## Room Description:
In this room we will cover the basics of networking. We learn about what is networking why understanding networking concepts in cybersecurity is important.

## Goal:
- Understanding Networking and its basics.
- Importance of Networking in cyber security

## Task 1: What is Networking?

### Networking:
In computer system networking refers to the connection between devices. Networking is the process of connecting computers and device so they can communicate and share data.

Let me clear it by an example Networks are simply things connected together like our friend circle we connected with each other because we have similar data like skills, hobbies, and intrests.

In computing take example of Mobile phone when we want to send a whatsapp message to someone from our phone, it travel through the internet to whatsapp's server and then to friend phone this communication is networking.

**Question:** What is the key term for devices that are connected together?  
**Answer:** Network


## Task 2: What is Internet?
The internet is a global network of networks. It is one gaint network that consist many networks.
The internet began with ARPANET project in the late 1960's, funded by US Deparmtent of Defense when Tim Berners-Lee introduce (WWW) word wide web.
Internet is divide into many small networks called private network and these small networks connect to make public network or the internet.

**Question:** Who invented the World Wide Web?  
**Answer:** Tim Berners-Lee


## Task 3: Identifying Devices on a Network
For holding communication both device must identifiable and know each other.
Every device on a network has two identities;
1. IP Address
2. MAC Address

### IP Address:
IP stands for Internet Protocol. IP is a logical identifier to locate a device on a network. It is a numerical identifier assinged to a device on a network.
IP address is a set of number that are divided into four octets and each octet is seperated by Dot(.) and the values is assigned based on a special technique know as IP addressing and subneting.
### Example:
Octet#1	Octet#2	Octet#3	Octet#4  
192.	168.	80.	200  
0-255	0-255	0-255	0-255  

IP addresses follow a set of rule known as protocols and these protocol is a backbone of networking and these protocol force all devices to communicate in the same language.
There are two types of IP addresses;
1. Public IP
2. Private IP

### MAC Address:
Media Access Control is a unique physical identifier assingned to a device's Network inerface (NIC) by manufactures. NIC is a small pysical chip on the device's motherboard. The MAC address is 12 character hexadecimal number which is slpit into 2's and seperated by a colon (:)
### Example:
a1:b2:c3:d4:e5:f6  
The first six represents the company made the NIC and the last six a unique number assigned to device.

**Question:** What does the term "IP" stand for?  
**Answer:** Internet Protocol

**Question:** What is each section of an IP address called?  
**Answer:** Octet

**Question:** How many sections (in digits) does an IPv4 address have?  
**Answer:** 4

**Question:** What does the term "MAC" stand for?  
**Answer:** Media Access Control

**Question:** Deploy the interactive lab using the "View Site" button and spoof your MAC address to access the site.  What is the flag?  
**Answer:** THM{*************}



## Task 4: Ping (ICMP):
Ping is a network tool used to test the conectivity of a devices. Ping uses ICMP (Ineternet Control Message Protocol) to determine the the connectivity of two devices.
#### Example:
ping google.com
ping <IP>

**Question:** What protocol does ping use?  
**Answer:** ICMP

**Question:** What is the syntax to ping 10.10.10.10?  
**Answer:** ping 10.10.10.10

**Question:** What flag do you get when you ping 8.8.8.8?  
**Answer:** THM{***************}

