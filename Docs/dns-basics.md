# DNS Basics

## What is DNS?

DNS (Domain Name System) translates human-readable domain names into IP addresses.

Example:

google.com → 142.250.183.78

## Why DNS is Important

Without DNS, users would have to remember IP addresses instead of domain names.

## DNS Resolution Process

1. User enters a domain name.
2. Browser checks its cache.
3. Request is sent to a recursive DNS resolver.
4. Resolver queries the Root DNS server.
5. Root server directs it to the TLD server.
6. TLD server directs it to the authoritative DNS server.
7. The authoritative server returns the IP address.
8. The browser connects to the website.

## Common DNS Record Types

* A – IPv4 Address
* AAAA – IPv6 Address
* MX – Mail Server
* CNAME – Alias
* TXT – Text Record
* NS – Name Server
