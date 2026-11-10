COMMON NETWORK PROTOCOLS – COMPLETE CHEATSHEET
1. Introduction to Network Protocols
A network protocol is a set of rules and standards that allows computers and other devices to communicate and exchange data over a network.

Definition:
Network protocols are predefined rules that control how data is transmitted, received, and processed between devices in a computer network.
Importance of Network Protocols
1. Enable communication between computers.
2. Ensure proper data transmission.
3. Provide data security.
4. Control data flow.
5. Help identify devices on a network.
6. Reduce communication errors.
2. Common Network Protocols
1. HTTP (Hypertext Transfer Protocol)
- Used for transferring web pages over the internet.
- Allows communication between web browsers and web servers.
- Uses TCP port 80.
- It does not encrypt communication by itself.
Example: Opening a normal HTTP website.
2. HTTPS (Hypertext Transfer Protocol Secure)
- Secure version of HTTP.
- Uses encryption to protect communication.
- Uses TCP port 443.
- Commonly uses TLS for security.
Example: Online banking and secure websites.
3. FTP (File Transfer Protocol)
- Used to transfer files between computers.
- Allows uploading and downloading files.
- Uses TCP ports 20 and 21 in traditional active mode.
Example: Transferring files to a server.
4. SFTP (SSH File Transfer Protocol)
- Used for secure file transfer.
- Works over SSH.
- Uses TCP port 22 by default.
- Provides encrypted file transfers.
Example: Securely transferring files to a remote server.
5. SMTP (Simple Mail Transfer Protocol)
- Used for sending emails from clients to mail servers and between mail servers.
- Common ports: 25, 465 and 587.
- Port 587 is commonly used for email submission.
Example: Sending an email.
6. POP3 (Post Office Protocol Version 3)
- Used to retrieve emails from a mail server.
- Commonly downloads messages to a local device.
- Uses TCP port 110.
- Secure version commonly uses port 995.
Example: Downloading emails to an email application.
7. IMAP (Internet Message Access Protocol)
- Used to access and manage emails stored on a mail server.
- Keeps messages synchronized across multiple devices.
- Uses TCP port 143.
- Secure version commonly uses port 993.
Example: Accessing the same email account on a phone and computer.
8. TCP (Transmission Control Protocol)
- Provides reliable data transmission.
- Establishes a connection before transferring data.
- Ensures data arrives in the correct order.
- Used by HTTP, HTTPS, FTP and SMTP.
Example: Reliable communication between web browsers and servers.
9. UDP (User Datagram Protocol)
- Provides fast, connectionless data transmission.
- Does not guarantee delivery or packet order.
- Has lower communication overhead than TCP.
Example: Online gaming, live streaming and voice calls.
10. IP (Internet Protocol)
- Responsible for addressing and routing data packets.
- Helps deliver data from source to destination.
- Main versions are IPv4 and IPv6.
Example: Sending data between computers over the internet.
11. DNS (Domain Name System)
- Converts domain names into IP addresses.
- Makes websites easier to access.
- Uses port 53 (UDP and TCP).
Example: Converting google.com into an IP address.
12. DHCP (Dynamic Host Configuration Protocol)
- Automatically assigns IP addresses to network devices.
- Provides network configuration information.
- Uses UDP ports 67 and 68.
Example: Automatically receiving an IP address when connecting to Wi-Fi.
13. SSH (Secure Shell)
- Provides secure remote access to computers.
- Encrypts communication.
- Uses TCP port 22.
Example: Managing a remote Linux server.
14. Telnet
- Used for remote access to computers.
- Transfers data without encryption.
- Uses TCP port 23.
Example: Remote command-line access in older systems.
15. SNMP (Simple Network Management Protocol)
- Used to monitor and manage network devices.
- Helps administrators check network performance.
- Uses UDP ports 161 and 162.
Example: Monitoring routers and switches.
16. ICMP (Internet Control Message Protocol)
- Used for sending network error and diagnostic messages.
- Helps identify network connectivity problems.
- Used by the ping command.
Example: Checking whether a computer is reachable using ping.
17. NTP (Network Time Protocol)
- Used to synchronize the clocks of computers over a network.
- Uses UDP port 123.
Example: Automatically updating the system time.
18. ARP (Address Resolution Protocol)
- Used in IPv4 networks to find the MAC address associated with a local IPv4 address.
- Works within a local network.
- Does not use TCP or UDP ports.
Example: Finding the MAC address of another device on a LAN.
3. Network Protocols and Their Port Numbers
This table is important for examinations and practical networking.
Protocol	Full Form	Port Number
HTTP	Hypertext Transfer Protocol	80
HTTPS	Hypertext Transfer Protocol Secure	443
FTP	File Transfer Protocol	20, 21
SFTP	SSH File Transfer Protocol	22
SSH	Secure Shell	22
Telnet	Teletype Network	23
SMTP	Simple Mail Transfer Protocol	25, 465, 587
DNS	Domain Name System	53
DHCP	Dynamic Host Configuration Protocol	67, 68
TFTP	Trivial File Transfer Protocol	69
POP3	Post Office Protocol 3	110, 995
IMAP	Internet Message Access Protocol	143, 993
SNMP	Simple Network Management Protocol	161, 162
LDAP	Lightweight Directory Access Protocol	389
LDAPS	LDAP over TLS	636
RDP	Remote Desktop Protocol	3389
NTP	Network Time Protocol	123


Note: Port numbers are standard defaults. Some protocols support different configurations.
4. Difference Between TCP and UDP
TCP	UDP
Transmission Control Protocol	User Datagram Protocol
Connection-oriented	Connectionless
Reliable transmission	Delivery is not guaranteed
Maintains packet order	Packet order is not guaranteed
More communication overhead	Less communication overhead
Uses acknowledgements	No built-in acknowledgements
Used in web browsing and file transfer	Used in gaming and live streaming


5. Classification of Network Protocols
Network protocols can be classified into different categories.
A. Communication Protocols
These protocols help devices communicate with each other.

Examples:
- TCP
- UDP
- IP
B. File Transfer Protocols
These protocols are used to transfer files between computers.

Examples:
- FTP
- SFTP
- TFTP
C. Email Protocols
These protocols are used for sending and receiving emails.

Examples:
- SMTP
- POP3
- IMAP
D. Security Protocols
These protocols help protect data and communication.

Examples:
- HTTPS
- SSH
- TLS
E. Network Management Protocols
These protocols help monitor and manage network devices.

Examples:
- SNMP
- ICMP
- NTP
6. Network Protocols According to OSI Layers
OSI Layer	Protocols
Application Layer	HTTP, HTTPS, FTP, SMTP, DNS, DHCP, POP3, IMAP, SNMP
Presentation Layer	TLS, SSL
Session Layer	NetBIOS, RPC
Transport Layer	TCP, UDP
Network Layer	IP, ICMP, IGMP
Data Link Layer	ARP, Ethernet, PPP
Physical Layer	Ethernet physical standards, Wi-Fi radio standards


Note: Some protocols operate across multiple layers or do not fit perfectly into the seven-layer OSI model.
7. Important Short Forms
Short Form	Full Form
LAN	Local Area Network
WAN	Wide Area Network
MAN	Metropolitan Area Network
IP	Internet Protocol
TCP	Transmission Control Protocol
UDP	User Datagram Protocol
DNS	Domain Name System
DHCP	Dynamic Host Configuration Protocol
HTTP	Hypertext Transfer Protocol
HTTPS	Hypertext Transfer Protocol Secure
FTP	File Transfer Protocol
SMTP	Simple Mail Transfer Protocol
SSH	Secure Shell
MAC	Media Access Control
NIC	Network Interface Card
ISP	Internet Service Provider


8. Important Points to Remember
1. HTTP is used for web communication.
2. HTTPS provides secure web communication.
3. FTP is used for file transfer.
4. SMTP is used for sending emails.
5. POP3 and IMAP are used for receiving and accessing emails.
6. TCP provides reliable data transmission.
7. UDP provides connectionless data transmission.
8. DNS converts domain names into IP addresses.
9. DHCP automatically assigns IP addresses.
10. SSH provides secure remote access.
11. ICMP is used for network diagnostics.
12. SNMP is used for network management.
13. NTP synchronizes system clocks.
14. ARP finds MAC addresses in IPv4 local networks.
9. Conclusion
Network protocols are essential for communication between computers and other devices. They define the rules for transferring data, sending emails, browsing websites, sharing files, and maintaining network security.

Different protocols perform different functions, and together they make communication over the internet and local networks possible.

END OF NOTES