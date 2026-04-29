# DNS Server Configuration and Testing

## Student Details

* Name: Shubham
* Roll Number: 2301730100

## Objective

To configure and test a DNS server using Cisco Packet Tracer for resolving domain names into IP addresses.

## Tools Used

* Cisco Packet Tracer

## Network Design

* Devices Used:

  * 1 Server (DNS Server)
  * 2 PCs
  * 1 Switch

## IP Configuration

* DNS Server: 192.168.1.2
* PC1: 192.168.1.3
* PC2: 192.168.1.4

## DNS Configuration

* DNS Service: Enabled
* Records Added:

  * [www.example.com](http://www.example.com) → 192.168.1.2
  * [www.google.com](http://www.google.com) → 8.8.8.8

## Testing Commands

* ping [www.example.com](http://www.example.com)
* nslookup [www.example.com](http://www.example.com)
* tracert [www.example.com](http://www.example.com)

## Result

The DNS server was successfully configured. Domain names were resolved into correct IP addresses, and connectivity was verified using ping and nslookup commands.

## Conclusion

This experiment helped in understanding how DNS works and how domain names are translated into IP addresses in a network.
