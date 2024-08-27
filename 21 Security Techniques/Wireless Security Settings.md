# Wired Equivalent Privacy (WEP)

Outdated 1999 wireless security standard meant to match wired LAN security for wireless networks

64-bit WEP

Consists of 40 bits of actual key data plus an extra 24 bits of initialization vector

128-bit WEP

Includes 104 bits of key datan an additional 24 bits of initialization vector

(WEP ins insecure and should be avoided because it's vulnerable to simple cryptographic attacks)

Insecure because of a weak 24-bit initialization vector

# Wi-Fi Protected Access (WPA)

Introduced in 2003 as a t emporary improvement over WEP while the more robust IEEE 802.11i standard was in development

Improved security over WEP with TKIP, which generates new 128-bit keys for each packet, eliminating WEP's key-reuse vulnerabilities

(Insecure because of t he lack of sufficient data integrity checks in the TKIP implementation)

# Wi-Fi Protected Access 2 (WPA2)

Improved data protection and network access control by addressing weaknesses in WPA version

Replaced WPA's TKIP with the AES protocol and adopted CCMP for stornger encryption

(Vulnerable to the KRACK Attack in 2016)

# Wi-Fi Protected Access 3 (WPA3)

Latest version using AES Encryption and introducing new features like SAE, Enhanced Open, updated cryptographic protocols, and management protection frames

Implements:

- [[Simultaneous Authentication of Equals (SAE)]]
- [[Enhanced Open/Opportunistic Wireless Encryption (OWE)]]
- [[Updated Cryptographic Protocols]]
  - [[Galois Counter Mode Protocol (GCMP)]]
- [[Management Protection Frames]]
- [[Authentication AUthorization and Accounting (AAA) Protocol]]

# Simultaneous Authentication of Equals (SAE)

Enhances security by offering a key establishment protocol to guard against offline dictionary attacks

# Enhanced Open/Opportunistic Wireless Encryption (OWE)

Major advancement in wireless security, especially for networks using open authentication

# Updated Cryptographic Protocols

Uses a newer variant of AES known as the AES [[Galois Counter Mode Protocol (GCMP)]]

# Galois Counter Mode Protocol (GCMP)

Supports 128-bit AES for personal networks and 192-bit AES for enterprise networks with WPA3

# Management Protection Frames

Required to protect network from key recovery attacks

- Prevents Eavesdropping, Forging, or Tampering, with frames.

# Authentication AUthorization and Accounting (AAA) Protocol

Plays a vital role in network security by centralizing user authenmtication to permit only authorized users to access network resources.

# Remote Authentication Dial-In User Service (RADIUS)

Client/server protocol offering AAA services for network users

# Terminal Access Controller Access-Conbtrol System Plus (TACACS+)

Separates the functions of AAA to allow for a more granular control over processes

# Authentication Protocols

Confirm user identity for network security and authorized access

# Extensible Authentication Protocol (EAP)

Authentication framework that supports multiple authentication methods

# Protected Extensible Authentication Protocol (PEAP)

Authentication protocol that securesEAP within an encrypted and authenticated TLS tunnel

# Extensible Authentication Protocol-Tunneled Transport Layer Security (EAP-TTLS)

Authentication protocol that extends TLS support across multiple platforms

# Extensible Authentication Protocol-Flexible AUthentication via Secure Tunneling (EAP-FAST)

Developed by Cisco, it enables secure re-authentication while roaming within a network without full authentication each time 

