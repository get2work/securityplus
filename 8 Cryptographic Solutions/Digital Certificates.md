# Digital Certificate

A digitally signed electronic document that binds a public key with a user's identity

# Wildcard Certificate
- Allows all of the subdomains to use the same public key certificate and have it displayed as valid
- Easy to manage, save money
- If revoked will also shutdown all ur subdomains

# Subject Alternate Name (SAN) field

Certificate that specifies what additional domains and IP addresses are going to be supported

# Single-Sided Certificate

Only requires the server to be validated

# Dual-Sided Certificate

Requires both the server and user to be validated

# Self-Signed Certificate

[[Digital Certificate]] that is signed by the same identity whose identity it certifies

# Third-Party Certificate

[[Digital Certificate]] issued and signewd by a trusted [[Certificate Authority]]

# Root of Trust

Each Certificate is validated using the concept of a root of trust or chain of trust

# Registration Authority (RA)

Requests identifying information from the user and forwards that certificate request up to the [[Certificate Authority]] to create the [[Digital Certificate]]

# Certificate Signing Request

A Block of encoded text that contains information about the entity requesting the certificate

# Certificate Revocation List (CRL)

Serves as an online list of digital certificates that the certificate authority has already revoked

# OCSP (Online Certificate Status Protocol)

Allows to determine the revocation status of any digital certificate using its serial number

# OCSP Stapling

Allows the certificate holder to ge tthe OCSP Record from the server at regular intervals

# Public Key Pinning

Allows an HTTPS Website to resist impersonation attacks from users who are trying to presentfraudulent certificates

# Key Escrow Agents

Occurs when a secure copy of a user's private key is being held

# Key Recovery Agent

Specialized type of software that allows the restoration of a lost or corrupted key to be performed