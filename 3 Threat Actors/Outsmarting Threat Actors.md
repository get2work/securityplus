# Tactics, Techniques and Procedures (TTPs)

- Specific methods and patterns of activities or behaviors associated with a particular threat actor or group of threat actors.

# Deception and Disruption Technologies

- Designed to mislead, confuse and divert attackers from critical assets while simultaneously detecting and neutralizing threats

- [[Honeyfiles]]
- [[Honeypots]]
- [[Honeynets]]
- [[Honeytokens]]
- [[Bogus DNS entries]]
- [[Decoy Directories]]
- [[Dynamic Page Generation]]
- [[Port Triggering]]
- [[Fake Telemetry Data]]

# Honeypots

Decoy systems or servers designed to attract and deceive potential attackers, simulating real-world IT assets to study their techniques

# Honeynets

Network of [[Honeypots]] to create a more complex system that is designed to mimic an entire network of systems, including servers, routers, and switches

- Logs all data about attacks
- THERE IS A RISK THAT THE ATTACKER COULD USE [[Honeypots]] and [[Honeynets]] to learn how production systems are configured

# Honeyfiles

Decoy watermarked files placed within systems to lure and detect unauthorized access or data breaches

# Honeytokens

A honeytoken is a piece of information or a system entity that is created to serve as a decoy or alert mechanism. A honeytoken's sole purpose is to be accessed or used illicitly, and any interaction with it is typically a clear sign of unauthorized activity, such as someone using a fake user account, a dummy email address, or a baited record in a database. It alerts the organization that someone has accessed the system.

# Bogus DNS entries

Fake DNS entries introduced into a system's DNS server

- Can lead attackers into accessing non-existent domains

# Decoy Directories

-Fake folders and files placed within a system's storage

# Dynamic Page Generation

- Used in websites to present ever-changing content to web crawlers to confuse and slow down the threat actor

# Port Triggering

- Security mechanism where specific services or ports on a network device remain closed until a specific outbound traffic partern is detected.

# Fake Telemetry Data

- System can respond to an attacker's netowrk scan attempt by sending out fake telemetry or network Data.

