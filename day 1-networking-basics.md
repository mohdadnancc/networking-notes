# Day 1 - Networking Basics

## Topics Learned

- What is a Network?
- What is the Internet?
- IP Address
- Public IP vs Private IP
- IPv4 vs IPv6
- Hostname
- DNS (Domain Name System)
- Ping
- nslookup
- Common Ports
  - SSH (22)
  - DNS (53)
  - HTTP (80)
  - HTTPS (443)

---

## Notes

### What is a Network?

A network is a group of devices connected together to share data and resources.

### What is the Internet?

The Internet is a global network that connects millions of computers and devices.

### IP Address

An IP Address is a unique address used to identify a device on a network.

Example:
- 192.168.1.10
- 172.24.51.25

### Public IP vs Private IP

Public IP
- Used on the Internet.
- Assigned by an Internet Service Provider (ISP).

Private IP
- Used inside local networks such as home or office.
- Example:
  - 192.168.x.x
  - 10.x.x.x
  - 172.16.x.x - 172.31.x.x

### IPv4 vs IPv6

IPv4
- 32-bit address
- Example: 192.168.1.1

IPv6
- 128-bit address
- Example: 2404:6800:4007:83f::200e

### Hostname

Hostname is the name of a computer on a network.

### DNS

DNS (Domain Name System) converts domain names into IP addresses.

Example:

google.com → 172.217.24.206

DNS uses Port 53.

### Ping

The ping command checks whether another device or server is reachable over the network.

### nslookup

The nslookup command finds the IP address of a domain using DNS.

---

## Commands Practiced

ip a
ip route
hostname
hostname -I
ping 8.8.8.8 -c 4
ping google.com -c 4
nslookup google.com
---

## Summary

Today I learned the basics of computer networking, including IP addresses, DNS, ping, nslookup, and common network ports.
