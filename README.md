
# TCP and UDP

## What is this project about?

In this project, I learned about TCP and UDP. They are two important protocols used for sending data over networks.

## TCP

TCP stands for Transmission Control Protocol.

It is used when reliable data transmission is important.

Some TCP features:
- It establishes a connection before sending data.
- It checks if data is received.
- It keeps data in the correct order.
- It can resend lost data.

TCP uses a Three-Way Handshake:
1. SYN
2. SYN-ACK
3. ACK

## UDP

UDP stands for User Datagram Protocol.

Unlike TCP, UDP does not establish a connection before sending data.

Some UDP features:
- It has lower overhead.
- It does not guarantee data delivery.
- It does not guarantee packet order.
- It is useful when low latency is important.

## TCP vs UDP

TCP focuses on reliable communication, while UDP focuses on simpler and faster data transmission.

Examples:
- TCP: SSH, FTP and traditional HTTPS.
- UDP: Online games, VoIP and many DNS queries.

## What I learned

I learned how TCP and UDP work, what makes them different, and why different applications use different protocols.

**Status:** Learning completed.
# cybersecurity-learning-journey
 cybersecurity learning journey, projects, research, and technical notes.

# Cybersecurity Learning Journey

Welcome to my cybersecurity learning portfolio!

I am building my knowledge in cybersecurity, computer networks, programming, and information security.

## Current Learning Topics

- Networking Fundamentals
- DNS and DNS Security
- TCP and UDP
- IP Addresses and Ports
- Cybersecurity Fundamentals

## Future Goals

- Learn Python programming
- Develop Linux skills
- Complete practical cybersecurity projects
- Participate in cybersecurity competitions
- Build a strong technical portfolio

## Projects

Projects and research will be added as I progress.

---

*Learning, practicing, and improving every day.*
DNS Resolution Process

DNS resolution translates a domain name into an IP address.

The main components are:

- Recursive Resolver: Handles DNS queries and returns the result.
- Root Server: Directs the resolver to the appropriate TLD server.
- TLD Server: Provides information about the domain's authoritative name server.
- Authoritative Name Server: Provides the official DNS records for the domain.

DNS Records

- A — IPv4 address
- AAAA — IPv6 address
- CNAME — Domain alias
- MX — Mail server
- TXT — Text information
- NS — Authoritative name servers

DNS Security

- DNS Spoofing
- DNS Cache Poisoning
- DNSSEC
Project 01 – DNS Fundamentals & Security
Status: In Progress
Main topic: DNS Resolution
Learned: DNS Components, DNS Records, DNS Security
Practical tools: nslookup
