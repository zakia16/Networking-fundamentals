# Networking Fundamentals

A curated collection of networking questions and answers explained in a simple, step-by-step manner.

## Table of Contents

- [Topics Covered](#topics-covered)
- [OSI & TCP/IP Models](#osi--tcpip-models)
- [SSL/ TLS](#ssl-tls)
- [Labs](#labs)

## Topics Covered

- OSI & TCP/IP models
- Networking basics
- DNS
- HTTP/HTTPS
- Security concepts

## OSI & TCP/IP Models

![OSI Model](https://github.com/user-attachments/assets/8bba6a34-c944-4fd3-9b41-92d72a660abc)

![OSI vs TCP/IP](https://github.com/user-attachments/assets/48efae0a-bb63-460b-b6d5-c0f9a25d87f3)

![OSI vs TCP/IP](https://github.com/user-attachments/assets/be411a89-76cf-480c-bc4b-e9edd4ef6e47)

## SSL/ TLS

![SSL/ TLS](https://github.com/user-attachments/assets/b383acaa-efd7-4170-b08a-a0f864474fc7)

### Resource
- **Video:** [What is SSL & TLS ? What is HTTPS ? What is an SSL VPN? - Practical TLS](https://www.youtube.com/watch?v=HMoFvRK4HUo)

### Key Security Concepts

* **SSL vs. TLS:** * **SSL (Secure Sockets Layer)** was originally created by Netscape in 1994 to add security to the early web [00:05:05]. 
  * In 1999, the **IETF (Internet Engineering Task Force)** took over maintenance of the protocol and renamed it to **TLS (Transport Layer Security)** [00:05:13]. 
  * While they refer to different historical versions, the terms are frequently used interchangeably today, though modern implementations strictly use TLS [00:05:41].
  * Both protocols function by creating a **secure, encrypted tunnel** across the untrusted infrastructure of the internet to protect data from intermediaries like ISPs or attackers [00:03:09].

* **HTTPS (Hypertext Transfer Protocol Secure):** * Standard **HTTP** transfers web pages (written in HTML) across the internet as plain text, meaning passwords or credit card information are entirely exposed to anyone in the transit path [00:02:25]. 
  * **HTTPS** is an HTML webpage transferred using the standard HTTP protocol but completely wrapped inside and secured by a protective TLS/SSL tunnel [00:03:24].

* **SSL VPN:** * Aside from securing web traffic, TLS/SSL can protect any other type of data transit via a Virtual Private Network (VPN) [00:03:44].
  * **Corporate Use Case:** Allows a remote client to build a secure tunnel over the internet into a corporate firewall, enabling safe access to private databases, internal files, or corporate emails [00:03:52].
  * **Public/Privacy Use Case:** Allows users to build a secure tunnel to a public VPN provider (e.g., ExpressVPN, NordVPN), effectively hiding the client's true IP address and masking their physical location [00:04:13].

![SSL/ TLS](https://github.com/user-attachments/assets/59cfa319-4319-4d38-820d-931717e12145)

## Labs

- **SEED Security Labs (Ubuntu 20.04):** [https://seedsecuritylabs.org/Labs_20.04/](https://seedsecuritylabs.org/Labs_20.04/)
