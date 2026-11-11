IPv4 IP Address – Types and Classes (Computer Networking )
1. What is an IP Address?
IP stands for Internet Protocol. An IP address is a unique logical address assigned to a device connected to a computer network.

It is used to identify devices and helps transfer data from one device to another over a network.

Example: 192.168.1.1

There are two main versions of IP addresses:
1. IPv4 (Internet Protocol Version 4)
2. IPv6 (Internet Protocol Version 6)
2. IPv4 Address
IPv4 stands for Internet Protocol Version 4. It is the fourth version of the Internet Protocol and is widely used in computer networks.
Features of IPv4
1. IPv4 uses a 32-bit address.
2. It is represented in decimal format.
3. It contains four parts separated by dots.
4. Each part contains 8 bits.
5. Each part has a value between 0 and 255.
6. It supports approximately 4.3 billion unique addresses.
Example:
192.168.1.1

Binary representation:

11000000.10101000.00000001.00000001
3. Types of IP Addresses
IP addresses are divided into different types according to their use.
A. Public IP Address
A public IP address is an address used to identify a network or device on the internet.

Features:
- Assigned by an Internet Service Provider (ISP).
- Used for internet communication.
- Globally unique.
Example: 8.8.8.8
B. Private IP Address
A private IP address is used inside a local network, such as a home, school, or office network.

Features:
- Used for communication within a local network.
- Not directly accessible from the public internet.
- Can be reused in different private networks.
Private IPv4 ranges:
- Class A: 10.0.0.0 – 10.255.255.255
- Class B: 172.16.0.0 – 172.31.255.255
- Class C: 192.168.0.0 – 192.168.255.255
C. Static IP Address
A static IP address is an IP address that remains fixed unless it is manually changed or its reservation is modified.

Features:
- Does not normally change.
- Can be manually configured.
- Useful for servers and network devices.
D. Dynamic IP Address
A dynamic IP address is automatically assigned to a device by a DHCP server.

Features:
- Assigned automatically.
- May change over time.
- Easy to manage in large networks.
4. Classes of IPv4 Addresses
IPv4 addresses are traditionally divided into five classes: A, B, C, D and E.

Each class has a different range and purpose.
Class A
- First octet range: 1–126.
- Used for very large networks.
- Default subnet mask: 255.0.0.0.
- Network bits: 8.
- Host bits: 24.
Example: 10.0.0.1
Class B
- First octet range: 128–191.
- Used for medium-sized networks.
- Default subnet mask: 255.255.0.0.
- Network bits: 16.
- Host bits: 16.
Example: 172.16.0.1
Class C
- First octet range: 192–223.
- Used for small networks.
- Default subnet mask: 255.255.255.0.
- Network bits: 24.
- Host bits: 8.
Example: 192.168.1.1
Class D
- First octet range: 224–239.
- Used for multicast communication.
- Does not have a default subnet mask.
Example: 224.0.0.1
Class E
- First octet range: 240–255.
- Reserved for experimental and research purposes.
- Not normally used for regular host addressing.
Example: 240.0.0.1
5. IPv4 Address Classes Table
Class	First Octet Range	Default Subnet Mask	Network Use
A	1–126	255.0.0.0	Large networks
B	128–191	255.255.0.0	Medium networks
C	192–223	255.255.255.0	Small networks
D	224–239	Not applicable	Multicasting
E	240–255	Not applicable	Experimental


Note: 127.x.x.x is reserved for loopback testing. It is not used as a normal Class A network address.
6. Special IPv4 Addresses
Some IPv4 addresses are reserved for special purposes.
IP Address	Purpose
127.0.0.1	Loopback address
0.0.0.0	Unspecified address
255.255.255.255	Limited broadcast address
169.254.x.x	Link-local address
192.168.1.1	Common private network address


7. Difference Between Public and Private IP Addresses
Public IP	Private IP
Used on the internet.	Used in local networks.
Globally unique.	Can be reused in different networks.
Assigned by ISP.	Usually assigned by router or network administrator.
Internet-routable.	Not directly internet-routable.
Example: 8.8.8.8	Example: 192.168.1.1


8. Advantages of IPv4
1. Easy to configure.
2. Widely supported by network devices.
3. Compatible with most existing networks.
4. Provides a standard addressing system.
5. Supports both public and private addressing.
9. Disadvantages of IPv4
1. Limited number of IP addresses.
2. Requires NAT in many networks.
3. Address management can be difficult.
4. Security is not built into the basic IPv4 protocol.
10. Conclusion
IPv4 is an important part of computer networking. It uses 32-bit addresses to identify devices on a network. IPv4 addresses can be public, private, static, or dynamic. They are traditionally divided into five classes: A, B, C, D, and E. Each class has a different address range and purpose.