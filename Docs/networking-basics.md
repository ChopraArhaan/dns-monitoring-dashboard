# Networking Basics

## What is a Network?

A network is a group of devices connected together to exchange data.

Examples include:

* Home Wi-Fi
* College LAN
* The Internet

---

## What is TCP/IP?

TCP/IP is the collection of communication protocols used on the Internet.

* IP (Internet Protocol) identifies devices using IP addresses.
* TCP (Transmission Control Protocol) provides reliable communication.
* UDP (User Datagram Protocol) provides fast communication without guaranteeing delivery.

---

## TCP vs UDP

### TCP

* Connection-oriented
* Reliable
* Guarantees packet delivery
* Performs error checking
* Slower than UDP

Common Uses:

* HTTP
* HTTPS
* FTP
* SSH

---

### UDP

* Connectionless
* Faster than TCP
* No delivery guarantee
* Lower overhead

Common Uses:

* DNS
* Video streaming
* Online gaming
* VoIP

---

## Ports

Ports identify which application receives network traffic.

Examples:

* 20/21 – FTP
* 22 – SSH
* 25 – SMTP
* 53 – DNS
* 80 – HTTP
* 443 – HTTPS

---

## DNS and Port 53

DNS primarily uses UDP on Port 53 because DNS queries are usually small and speed is important.

DNS uses TCP on Port 53 for:

* Zone transfers
* Responses that are too large for UDP
* Some DNSSEC-related communication

---

## Summary

Understanding TCP, UDP, IP addressing, and ports is essential before building a DNS monitoring application because DNS traffic is transmitted over these protocols.
