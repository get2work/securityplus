# Port Security

Common Network Security feature found on network switches that allows administrators to restrict which devices can connect to a specific port based on the network interface card's MAC address
- Switches use intelligence to prevent network collisions
- Switches are more efficient and secure than hubs

- Also implement 802.1x Authentication
- Extensible Authentication Protocol
  
# Content Addressable Memory (CAM) Table

Used to store information about the MAC addresses that are available on any given port of the switch

- MAC Flooding attack: causes an overflow of the mac table by flooding it with randomized mac addresses. Can overfill the cam table and itll fail open and lose its security. To prevent this attack enable port security or mac filtering.

- [[Port Security]] links MAC addresses to specific network interfaces for enhanced network security

# Persistent (Sticky) MAC Learning

Feature in network port security where the switch automatically learns and associates MAC addresses with specific interfaces

# 802.1x Protocol

Standardized framework that is used for port-based authentication for both wired and wireless networks.

Usually used at the Data Link Layer (Layer 2 of the OSI (Open Systems Interconnection) model)

- Uses RADIUS or TACACS+
- Can also be used to encapsulate [[EAP (Extensible Authentication Protocol)]]
- Requires the use of 3 different roles
- Supplicate: Device or user requesting access
- Authenticator: NEtwork Switch, Wireless Access POint, VPN Concentrator
- Authentication Server: Conficured as a RADIUS or TACACS+ server ([[RADIUS]] , [[TACACS+]])
- Top-notch defense against unauthorized access on the network

# RADIUS

cross-platform and faster than [[TACACS+]] but doesnt support Remote Access Protocol, NetBIOS frame protocol, or X.25 PAD COnnections

# TACACS+
(Cisco-proprietary protocol) (CISCO devices only)
(TACACS+ Slower due to using TCP but improved security, and supports all access protocols)

# EAP (Extensible Authentication Protocol)

Framework in a serious of protocols that allows for the numerous different ways for us to conduct authentication, including Simple Passowrds, Digital Certificates, and Public Key Infrastructures (PKI)

- [[EAP-MD5]]
- [[EAP-TLS]]
- [[EAP-TTLS]]
- [[EAP-FAST (Flexible Authentication via Secure Tunneling)]]
- [[PEAP]]
- [[LEAP (Lightweight EAP)]]
  
# EAP-MD5

Variant that utilizes simple passwords and the challenge handshake authentication process to provide remote access authentication

# EAP-TLS

Form of EAP that uses public key infrastructure (pki) with a digital certificate being installed on both the client and the server as the method of authentication

# EAP-TTLS

Variant that requires a digital certificate on the server, but not on the client

# EAP-FAST (Flexible Authentication via Secure Tunneling)

Variant that uses a protected access credential, instead of a certificate, to establish mutual authentication between devices

# PEAP

Variant that supports mutual authentication by using server certificates and the Microsoft Active Directory databases for it to authenticate a password from the client

# LEAP (Lightweight EAP)

Variant of EAP that only works on Cisco-based devices