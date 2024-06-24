# Zero Trust

Security model that operates on the principle that no one, whether inside or outside the organization, should be trusted by default

"Trust nothing and verify everything"

Demand verification for every device, user, and transaction within the network, regardless of its origin

Implement the [[Control Plane]] and the [[Data Plane]]

Cybersecurity approach that assumes no user/system is trusted by default and requires continuous verification for access to organizational resources

# Control Plane

The overarching framework and set of components responsible for defining, managing, and enforcing the policies related to user and system access within an organization

1. [[Adaptive Identity]]
2. [[Threat scope reduction]]
3. [[Policy-Driven Access Control]]
4. [[Secured Zones]]

Will use a [[Policy Engine]] and a [[Policy Administrator]]

# Policy Engine
Cross-References the access request with its predefined policies

# Policy Administrator
Used to establish and manage the access policies

Dictates who gets access to what

# Adaptive Identity
-Use adaptive identities that reply on real-time validation that takes into account the user's behavior, device, location, and more

# Threat scope reduction
-Limit the user's access to only what they need for their work tasks because this drastically reduces the networks attack scale

# Policy-Driven Access Control
-Entails developing, managing, and enforcing user access policies based on their roles and responsibilities

# Secured Zones
-Isolated Environments within a network that are designed to house sensitive data

# Data Plane

Focuses on the [[Subject/System]], [[Policy Engine]], [[Policy Administrator]], and establishing [[Policy Enforcement Point]]

# Subject/System

Refers to the individual or entity attempting to gain access

# Policy Enforcement Point

Allow or restrict access, and it will effectively act as a gatekeeper to the sensitive areas of the systems or networks