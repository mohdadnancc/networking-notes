# Day 1 - Default Gateway, DHCP and Subnet Basics

## Date

07 July 2026

---

## Topics Learned

- Default Gateway
- DHCP (Dynamic Host Configuration Protocol)
- Static IP
- Dynamic IP
- Subnet Mask (Introduction)
- CIDR Notation (Introduction)

---

## Notes

### Default Gateway

A Default Gateway is the IP address of a router that forwards network traffic from a local network to other networks, such as the Internet.

Example:

- My Default Gateway: 172.24.48.1

---

### DHCP (Dynamic Host Configuration Protocol)

DHCP automatically assigns network settings to devices.

It provides:

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server

---

### Static IP

A Static IP address is manually configured and does not change.

Commonly used for:

- Servers
- Network Devices
- Printers

---

### Dynamic IP

A Dynamic IP address is automatically assigned by a DHCP server.

Commonly used for:

- Laptops
- Desktop Computers
- Mobile Phones

---

### Subnet Mask

A Subnet Mask is used to identify the network portion and host portion of an IP address.

Example:

IP Address: 172.24.51.25/20

CIDR /20 represents the subnet size.

---

### CIDR (Classless Inter-Domain Routing)

CIDR is a shorter way to represent a subnet mask.

Examples:

| CIDR | Subnet Mask |
|------|-------------|
| /8   | 255.0.0.0 |
| /16  | 255.255.0.0 |
| /24  | 255.255.255.0 |

---

## Commands Practiced

ip route
ip a
cat /etc/resolv.conf
---

## Summary

Today I learned how devices access the Internet using a Default Gateway, how DHCP automatically provides network settings, the difference between Static and Dynamic IP addresses, and the basics of Subnet Masks and CIDR notation.
