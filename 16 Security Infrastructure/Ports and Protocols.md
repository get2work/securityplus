# Port

Logical communication endpoint that exists on a computer or a server
 - Inbound port
 - Outbound port
 - Can be anywhere from 0-65535

# Inbound port

Logical communication opening on a server that is listening for a connection from a client

# Outbound Port

Logical communication opening created ona  client in order to call out to a server that is listening for a connection

# Well-Known Ports

Ports 0 to 1023 are considered well-known and are assigned by the Internet Assigned Numbers Authority (IANA)

# Registered Ports

Ports 1024 to 49151 are considered registered and are usually assigned to proprietary protocols

- SQL: Port 1433
- RDP: Port 3389

# Dynamic and Private Ports

Port 49152 - 65535 can be used by any application without being registered with IANA

# Protocol

Rules governing device communication and data exchange

# Things to Memorize for Ports and Protocols

1. Port Number
2. Protocol Used by port
3. Know whether the port supports TCP/UDP
4. Basic Description

# Port 21 (TCP)
- File Transfer Protocol (FTP)
- Used to transfer files from host to host
- use port 22 instead
  
# Port 22 (TCP)
- SSH, SCP, and SFTP

- Provides secure remote terminal access and file transfer capabilities.
- Provides secure copy functions
- Provides secure file transfers

# Port 23 (TCP)
- Telnet
- Provides insecure remote control of another machine using a text-based environment
- Insecure, close telnet use ssh instead

# Port 25 (TCP)

- Simple Mail Transfer Protocol (SMTP)
- Provides the ability to send emails over the network

# Port 53 (TCP AND UDP)
- Domain Name System (DNS)
- Translates domain names into IP addresses

# Port 69 (UDP)
- Trivial File Transfer Protocol (TFTP)
- Used as a lightweight file transfer method for sending configuration files or network booting of an operating system

# Port 80 (TCP)
- Hypertext Transfer Protocol (HTTP)
- Used for insecure web browsing

# Port 88 (UDP)
- Kerberos
- Network authentication protocol

# Port 110 (TCP)
- Post office protocol version three (POP3)
- Responsible fo retrieving email from a server

# Port 119 (TCP)
- Network News Transfer Protocol (NNTP)
- Used for accessing newsgroups

# Port 135 (TCP and UDP)
- Remote Procedure Call (RPC)
- Facilitates communication between different system processes

# Port 137, 138, and 139 (TCP and UDP)
- NetBIOS
- Networking protocol suite

# Port 143 (TCP)
- Internet Messages Access Protocol (IMAP)
- Allows access to email messages on a server

# Port 161 (UDP)
- Simple Network Management Protocol (SNMP)
- Manages network devices

# Port 162 (UDP)
- SNMP Trap
- Responsible for sending SNMP trap messages

# Port 389 (TCP)
- Lightweight Directory Access Protocol (LDAP)
- Facilitates directory services

# Port 443 (TCP)
- HTTP Secure (HTTPS)
- Provides secure web communication

# Port 445 (TCP)
- Server Message Block (SMB)
- Used for file and printer sharing over a network

# Port 465 and 587 (TCP)
- SMTP Secure (SMTPS)
- Provides secure SMTP communication

# Port 514 (UDP)
- Syslog
- Used for sending log messages

# Port 636 (TCP)
- LDAP Secure (LDAPS)
- LDAP communication over SSL/TLS

# Port 993 (TCP)
- Internet Message Access Protocol over SSL/TLS (IMAPS)
- Used for secure email retrieval

# Port 995 (TCP)
- Post Office Protocol version 3 over SSL/TLS (POP3S)
- Used for secure email retrieval

# Port 1433 (TCP)
- Microsoft SQL
- Used to facilitate communication with Microsoft SQL Server

# Port 1645 and 1646 (TCP)
- RADIUS TCP
- Used for remote authentication, authorization, and accounting

# Port 1812 and 1813 (UDP)
- RADIUS UDP
- Used for authentication and accounting as defined by the internet Engineering Task Force (IETF)

# Ports 3389 (TCP)
- Remote Desktop Protocol (RDP)
- Enables remote desktop access

# Port 6514 (TCP)
- Syslog TLS
- Used in a secure syslog that uses SSL/TLS to encrypt the IP packets using a certificate before sending them across the IP network to the syslog collector


