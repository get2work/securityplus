# Data at Rest
 - Refers to any data stored in databases, file systems, or other storage systems
 - Prime target for threat actors
 - [[Encryption]] is a good type of protection for this data
   - [[Full disk encryption (FDE)]]
   - [[Partition Encryption]]
   - [[File Encryption]]
   - [[Volume Encryption]]
   - [[Database Encryption]]
   - [[Record Encryption]]
  
# Data in Transit/Data in Motion
- Refers to the data actively moving from one location to another, such as across the Internet or through a private network.
  - [[Secure Sockets Layer (SSL)]] and [[Transport Layer Security (TLS)]]
  - [[Virtual Private Network (VPN)]]
  - [[Internet Protocol Security (IPSec)]]


# Data in Use

Refers to data in the process of being created, retrieved, updated, or deleted
    - [[Application Level Encryption]]
    - [[Access Controls]]
    - [[Secure Enclaves]]
    - [[Intel Software Guards (SGX)]]

# Full disk encryption (FDE)

Encrypts the entire hard drive

# Partition Encryption

Encrypts specific partitions of a hard drive, leaving other partitions unencrypted

# File Encryption

Encrypts Individual files

# Volume Encryption

Encrypts a set of selected files or directories

# Database Encryption

Encrypts a set of selected files or directories

# Record Encryption

Encrypts specific fields within a database record

# Secure Sockets Layer (SSL)

Secure Sockets Layer (SSL) is a cryptographic protocol that provides secure communication over a computer network. It ensures that the data transmitted between a client and a server is encrypted and protected from unauthorized access.

SSL uses a combination of symmetric and asymmetric encryption algorithms to establish a secure connection. It provides authentication, confidentiality, and integrity of data, protecting against eavesdropping, tampering, and forgery.

To use SSL, both the client and the server must support the protocol and have a valid digital certificate. The certificate is used to verify the identity of the server and establish a secure connection.

SSL has been deprecated due to security vulnerabilities, and Transport Layer Security (TLS) has been developed as its successor. It is recommended to use TLS instead of SSL for secure communication over a network.

# Transport Layer Security (TLS)

Transport Layer Security (TLS) is a cryptographic protocol that provides secure communication over a network. It ensures the privacy and integrity of data transmitted between two endpoints, such as a client and a server. TLS is commonly used to secure web traffic, email communication, and other network protocols.

TLS operates at the transport layer of the OSI model and uses a combination of symmetric and asymmetric encryption algorithms to establish a secure connection. It provides authentication, confidentiality, and integrity of data, protecting against eavesdropping, tampering, and forgery.

To use TLS, both the client and the server must support the protocol and have a valid digital certificate. The certificate is used to verify the identity of the server and establish a secure connection. TLS also supports the negotiation of encryption algorithms and key exchange methods to ensure compatibility between the communicating parties.

TLS is considered more secure than SSL and offers stronger encryption algorithms, better compatibility, and improved security features. It is recommended to use TLS instead of SSL for secure communication over a network.

# Difference Between SSL and TLS

TLS (Transport Layer Security) and SSL (Secure Sockets Layer) are both cryptographic protocols that provide secure communication over a network. While they serve the same purpose, there are some key differences between the two.

1. Security: TLS is considered more secure than SSL. SSL has been deprecated due to security vulnerabilities, and TLS has been developed as its successor.

2. Versions: SSL has multiple versions, including SSL 2.0, SSL 3.0, and TLS 1.0. TLS has its own versions, such as TLS 1.1, TLS 1.2, and TLS 1.3.

3. Encryption Algorithms: TLS supports stronger encryption algorithms compared to SSL. TLS uses modern algorithms like AES (Advanced Encryption Standard) and SHA-2 (Secure Hash Algorithm 2), while SSL relies on older algorithms like RC4 and MD5.

4. Compatibility: TLS is backward compatible with SSL. This means that TLS can negotiate with SSL-enabled servers and clients to establish a secure connection. However, SSL cannot negotiate with TLS-only servers and clients.

5. Certificate Support: TLS requires the use of X.509 digital certificates for authentication. SSL also supports X.509 certificates but can also use other types of certificates.

In summary, TLS is the more secure and modern protocol compared to SSL. It offers stronger encryption algorithms, better compatibility, and improved security features. It is recommended to use TLS instead of SSL for secure communication over a network.

# Virtual Private Network (VPN)

Technology that creates a secure connection over a less secure network (Internet)

# Internet Protocol Security (IPSec)

Protocol suite used to secure IP communications by authenticating and encrypting each IP packet in a data stream.


# Secure Enclaves

Secure enclaves refer to isolated and protected environments where sensitive data and processes can be executed securely. These enclaves provide a trusted execution environment (TEE) that is isolated from the rest of the system, ensuring the confidentiality and integrity of the data and code within.

Secure enclaves typically rely on hardware-based security features, such as Intel Software Guard Extensions (SGX) or ARM TrustZone, to create a secure and isolated environment. These features provide hardware-level protection against unauthorized access, tampering, and side-channel attacks.

Within a secure enclave, sensitive operations can be performed, such as cryptographic operations, key management, and secure computations. The data processed within the enclave remains encrypted and protected, even from other processes running on the same system.

Secure enclaves are commonly used in scenarios where the confidentiality and integrity of sensitive data are critical, such as in cloud computing, remote attestation, and secure multiparty computation. They provide a strong level of security by isolating sensitive operations and data from potential threats, including malicious software and unauthorized users.

To utilize secure enclaves, developers need to design and implement their applications to leverage the specific hardware-based security features provided by the platform. This involves using appropriate APIs and frameworks to create and manage enclaves, as well as ensuring proper key management and secure communication channels.

Overall, secure enclaves offer a powerful mechanism for protecting sensitive data and executing critical operations in a secure and isolated environment. By leveraging hardware-based security features, they provide a high level of assurance and can significantly enhance the security posture of applications and systems.

# Access Controls

Access controls refer to the mechanisms and policies implemented to regulate and manage access to resources, systems, and data. They are essential for maintaining the confidentiality, integrity, and availability of information.

Access controls can be categorized into three main types:

1. **Physical Access Controls**: These controls restrict physical access to buildings, rooms, and equipment. Examples include locks, access cards, biometric authentication, and surveillance systems.

2. **Logical Access Controls**: These controls regulate access to computer systems, networks, and data. They ensure that only authorized individuals can access and perform specific actions on resources. Examples include usernames and passwords, two-factor authentication, access control lists (ACLs), and role-based access control (RBAC).

3. **Administrative Access Controls**: These controls involve policies, procedures, and guidelines that govern the overall management of access controls. They include processes for user provisioning, access request approvals, periodic access reviews, and security awareness training.

Access controls play a crucial role in preventing unauthorized access, data breaches, and insider threats. They help enforce the principle of least privilege, where users are granted only the minimum access necessary to perform their tasks. By implementing access controls, organizations can protect sensitive information, maintain regulatory compliance, and safeguard their systems and data from unauthorized access.

# Intel Software Guards (SGX)

Intel Software Guards (SGX) is a hardware-based security technology developed by Intel that provides a secure execution environment for applications. SGX allows developers to create secure enclaves, isolated regions of memory, where sensitive data and code can be stored and executed securely.

SGX leverages the trusted execution environment (TEE) provided by the CPU to protect the confidentiality and integrity of data within the enclaves. The enclaves are encrypted and isolated from the rest of the system, preventing unauthorized access and tampering.

Applications running within SGX enclaves can perform sensitive operations, such as cryptographic computations and key management, without exposing the data to potential threats. The data processed within the enclaves remains encrypted and protected, even from other processes running on the same system.

SGX provides hardware-level protection against various attacks, including side-channel attacks, memory tampering, and reverse engineering. It ensures that the code and data within the enclaves are protected from unauthorized access, even if the underlying system is compromised.

To utilize SGX, developers need to design and implement their applications to leverage the SGX APIs and SDK provided by Intel. This involves partitioning the application into trusted and untrusted components, with the sensitive operations performed within the enclaves.

Overall, Intel Software Guards (SGX) offers a powerful mechanism for protecting sensitive data and executing critical operations in a secure and isolated environment. By leveraging hardware-based security features, SGX provides a high level of assurance and can significantly enhance the security posture of applications and systems.

# Application Level Encryption

- Encrypts data at the application level, providing an additional layer of security
- Protects sensitive information within an application, such as passwords, credit card numbers, or personal data
- Uses encryption algorithms to transform the data into an unreadable format, which can only be decrypted with the appropriate key
- Helps prevent unauthorized access to sensitive data, even if the underlying storage or network is compromised
- Can be implemented through libraries, frameworks, or custom code within the application
- Provides end-to-end encryption, ensuring that data remains encrypted throughout its lifecycle
- Helps organizations comply with data protection regulations and maintain customer trust
- Requires proper key management and secure storage of encryption keys
- Can introduce some performance overhead, depending on the complexity of the encryption algorithms used
- Should be combined with other security measures, such as access controls and secure coding practices, for comprehensive data protection.