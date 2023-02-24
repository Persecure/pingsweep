# pingsweep

A ping sweep is a network scanning technique used to discover which IP addresses are active and can be reached by a particular device or network.

During a ping sweep, a device sends a series of Internet Control Message Protocol (ICMP) echo requests to a range of IP addresses. If an IP address is active and able to receive messages, it will respond to the echo request with an ICMP echo reply.

By analyzing the responses to the ICMP echo requests, a network administrator can determine which IP addresses are active and which are not. This information can be useful for troubleshooting network issues, identifying potential security threats, or mapping out the network topology.

However, it’s worth noting that some network configurations may block or filter ICMP traffic, which can make a ping sweep less effective or even completely ineffective.

**This is a simple bash script to ping an entire /24 network.

![image](https://user-images.githubusercontent.com/93418272/221205900-a15eaee0-0014-4e92-bc41-f8d1119b1664.png)
