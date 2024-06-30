# Virtual Private Network (VPN)

Extends a private network over a public one, enabling users to securely send and receive data across a shared or public network as if they were directly connected to the Private Network

Can be configured as:
- [[Site-to-site VPN]]
- [[Client-to-site VPN]]
- [[Clientless VPN]]

# Site-to-site VPN
Establishes secure tunnels over the public Internet for interconnecting remote sites

- Secures traffic, but may slow down users due to extra data transfer

# Client-to-site VPN

Connects individual devices directly to the organization's headquarters, enabling remote users to access the network

- [[Full Tunnel]]
- [[Split Tunnel]]

# Full Tunnel

Maximizes security by encrypting all traffic to the headquarters while integrating clients with the network

# Split Tunnel

Divides traffic and network requests and then routes them to the appropriate network

- Better Performance

# Clientless VPN

Secures remote access through browser-based VPN tunnels without needing client software or hardware configuration

Example: HTTPS
- [[Transport Layer Security (TLS)]]
  - Uses [[Transmission Control Protocol (TCP)]]
- [[Datagram Transport Layer Security (DTLS)]]
- [[Internet Protocol Security (IPSec)]]


# Transmission Control Protocol (TCP)

Used by TLS to establish secure connections between a client and a server, but it may slow down the connection

# Datagram Transport Layer Security (DTLS)

A UDP-based version of TLS protocol that offers the same security level as TLS while maintaining faster operations

Ensures end-user security and protects eavesdropping, fast and encrypted

# Authentication Header (AH)

Offers connectionless data integerity and data origin authentication for IP datagrams using cryptographic hash as identification information

# Encapsulating Security Payload (ESP)

Employed for providing authentication, integrity, replay protection, and data confidentiality by encrypting the packet's payload