# Network Intrusion Detection Systems (NIDS)

Responsible for detecting unauthorized network access or attacks

- Monitor the traffic coming in and out of a network

# Host-Based IDS (HIDS)

Looks at suspicious network traffic going to or from a single server or endpoint

# Wireless IDS (WIDS)

Focused on detecting attempts to cause a denial of service on a network

# Signature-based IDS

Analyzes traffic based on defined signatures and can only recognize attacks based on previously identified attacks in its database

- Not effective against Zero Day attacks

# Pattern-matching IDS
- Specific pattern of steps that are being recognized during an attack

More common in (NIDS, WIDS)

# Stateful-matching IDS

- Relies on a known baseline of a system, and reports any changes to that state
More common in (HIDS)

# Anomaly-based/Behavioral-based IDS

Analyzes traffic and compares it to a normal baseline of traffic to determine whether a threat is occuring

- Statistical
- Protocol
- Traffic
- Rule/Heuristic
- Application-based

# Intrusion Prevention Systems (IPS)

Scans traffic to look for malicious activity and takes action to stop it

