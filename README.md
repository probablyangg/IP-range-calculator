# IP-range-calculator
The program calculates IP Range, network id, host id, given IP address and CIDR value.

## Input

IP Address followed by Subnet Mask

```
Enter IPv4 Address: 192.168.1.1

Enter Subnet Mask for 192.168.1.1: 255.255.255.0
```

## Output 

```
------------------------------------------
~ Binary Representation ~
------------------------------------------
11000000.10101000.00000001.00000001  : IP Address
11111111.00000000.00000000.00000000  : Subnet Mask
-----------------------------------------

------------------------------------------
~ Class Information ~
------------------------------------------
IP Class: Private block, Class 'C'
Default Class Subnet Mask: 255.255.255.0
-----------------------------------------

------------------------------------------
~ Subnet Details ~
------------------------------------------
Network ID:            -           Broadcast ID:
-------------------------------------------------
192.0.0.0 - [ usable hosts ] - 192.255.255.255

Network Increment: 1
Number of Subnets: 1
Usable hosts per subnet: 16777214
-----------------------------------------
```