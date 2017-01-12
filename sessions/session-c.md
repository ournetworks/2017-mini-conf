# Session C: Build a Mesh Node: Meshing with cjdns and messing with secure-scuttlebutt

## Description

This hands-on session begins with [configuring a Raspberry Pi](https://github.com/tomeshnet/prototype-cjdns-pi2) as a [cjdns](https://github.com/cjdelisle/cjdns) mesh node. Then we will enable the [IP tunnel](https://en.wikipedia.org/wiki/IP_tunnel) feature to route all Internet traffic to another cjdns node through the [Hyperboria](https://github.com/hyperboria) encrypted mesh network.

We will run [secure-scuttlebutt](https://github.com/ssbc/secure-scuttlebutt) on our ad-hoc mesh, which keeps an append-only database on each node with peer-to-peer replication across the network, enabling mesh-friendly applications such as [Patchwork](https://github.com/ssbc/patchwork) and [dnssb](https://github.com/ansuz/dnssb). Join us at this workshop for some DIY peer-to-peer social networking and [DNS](https://en.wikipedia.org/wiki/Domain_Name_System) distribution!

If you have a Raspberry Pi 3, please bring that along with [Raspbian Jessie Lite](https://www.raspberrypi.org/downloads/raspbian/) pre-flashed, but that is not a prerequisite to participate and there will be limited number of Raspberry Pi's provided at the workshop.

## Session Objective

- Use the cjdns protocol to set up an encrypted mesh network of Raspberry Pi's
- Configure an IP tunnel to exit all Internet traffic at a distant cjdns node, essentially having the Raspberry Pi serve as a [VPN](https://en.wikipedia.org/wiki/Virtual_private_network) router
- Run secure-scuttlebutt applications: peer-to-peer social networking with Patchwork, and distributing DNS records among friends using dnssb

## Length

1:20

## Materials

- Laptop (not provided, please bring your laptop)
- Raspberry Pi 3 kit (6 kits for sharing, bring your own Raspberry Pi 3 if you have one)
- TP-LINK TL-WN722N WiFi USB adapter (provided)
- Ethernet cable (provided)

## Registration

40

## Presenter(s)

Name: ansuz  
Email: ansuz 4t transitiontech d0t see eh  
Twitter: [@fc00ansuz](https://twitter.com/fc00ansuz)  
GitHub: [ansuz](https://github.com/ansuz)  
Url(s): [transitiontech.ca](https://transitiontech.ca)

## Presenter Bio

ansuz is a Toronto-based hacker temporarily stuck in Paris.
