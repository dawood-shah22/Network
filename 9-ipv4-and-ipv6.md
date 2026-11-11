IPv4 and IPv6 – Computer Networking Notes
1. Introduction
IP stands for Internet Protocol. It is a set of rules used for communication between devices over a network.

An IP address is a unique logical address assigned to a device connected to a network. It helps identify devices and allows data to travel from one device to another.

There are two main versions of Internet Protocol:
1. IPv4 (Internet Protocol Version 4)
2. IPv6 (Internet Protocol Version 6)
2. IPv4 (Internet Protocol Version 4)
IPv4 stands for Internet Protocol Version 4. It is the fourth version of the Internet Protocol and is widely used in computer networks.
Features of IPv4
1. It uses a 32-bit address.
2. It is represented in decimal format.
3. It contains four groups separated by dots.
4. Each group contains numbers from 0 to 255.
5. It supports approximately 4.3 billion unique addresses.
6. It supports both public and private IP addresses.
Example of IPv4 Address
192.168.1.1

Another example:

172.16.0.1
Structure of IPv4
An IPv4 address contains 32 bits divided into four parts.

Example:

192.168.1.1

Each part contains 8 bits (1 byte).
Advantages of IPv4
- Easy to configure.
- Widely supported by network devices.
- Compatible with most existing networks.
- Simple addressing system.
Disadvantages of IPv4
- Limited number of IP addresses.
- Requires NAT (Network Address Translation) in many networks.
- Security features are not built into the basic protocol.
- Address availability is limited.
3. IPv6 (Internet Protocol Version 6)
IPv6 stands for Internet Protocol Version 6. It is the latest version of the Internet Protocol, developed to overcome the limitations of IPv4.

It provides a much larger address space and improves network communication.
Features of IPv6
1. It uses a 128-bit address.
2. It is represented in hexadecimal format.
3. It contains eight groups separated by colons.
4. It provides a very large number of IP addresses.
5. It supports automatic address configuration.
6. It provides built-in support for IPsec.
7. It improves routing efficiency.
Example of IPv6 Address
2001:0db8:85a3:0000:0000:8a2e:0370:7334
Structure of IPv6
An IPv6 address contains 128 bits divided into eight groups.

Each group contains 16 bits and is represented using hexadecimal numbers.
Advantages of IPv6
- Provides a huge number of IP addresses.
- Supports automatic configuration.
- Improves routing efficiency.
- Reduces the need for NAT.
- Supports IPsec.
- Better suited for modern internet-connected devices.
Disadvantages of IPv6
- More complex than IPv4.
- Requires updated network equipment and software in some environments.
- Not directly compatible with IPv4.
- Migration can be difficult and time-consuming.
4. Difference Between IPv4 and IPv6
IPv4	IPv6
IPv4 stands for Internet Protocol Version 4.	IPv6 stands for Internet Protocol Version 6.
Uses 32-bit addresses.	Uses 128-bit addresses.
Uses decimal format.	Uses hexadecimal format.
Contains four groups.	Contains eight groups.
Uses dots (.) as separators.	Uses colons (:) as separators.
Supports approximately 4.3 billion addresses.	Supports an extremely large number of addresses.
Configuration can be manual or automatic.	Supports automatic configuration.
Broadcast is supported.	Does not support broadcast.
NAT is commonly used.	NAT is generally not required.
Example: 192.168.1.1	Example: 2001:db8::1


5. Types of IP Addresses
A. Public IP Address
- Used to identify a network on the internet.
- Assigned by an Internet Service Provider (ISP).
- Can be accessed over the internet.
B. Private IP Address
- Used within local networks.
- Not directly accessible from the public internet.
- Commonly used in homes, schools, and offices.
C. Static IP Address
- An IP address that is manually configured or reserved.
- Usually remains unchanged.
D. Dynamic IP Address
- Automatically assigned to a device.
- Usually assigned through DHCP.
- May change over time.
6. IPv4 Address Classes
IPv4 addresses are traditionally divided into five classes.
Class	Address Range	Usage
Class A	1.0.0.0 – 126.255.255.255	Large networks
Class B	128.0.0.0 – 191.255.255.255	Medium networks
Class C	192.0.0.0 – 223.255.255.255	Small networks
Class D	224.0.0.0 – 239.255.255.255	Multicasting
Class E	240.0.0.0 – 255.255.255.255	Experimental purposes


Note: Classful addressing is an older system. Modern networks generally use CIDR (Classless Inter-Domain Routing).
7. Conclusion
IPv4 and IPv6 are two versions of the Internet Protocol used for communication over computer networks. IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses. IPv6 was developed to overcome the limited address space of IPv4 and support the growing number of internet-connected devices.

Important: IPv4 and IPv6 are essential topics in computer networking because they help us understand how devices communicate over the internet.