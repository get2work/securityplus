# Virtualization

Technology that allows for the emulation of servers

**Vulnerabilities:**
- [[VM Escape]]
- [[Privilege Elevation]]
- [[Live VM Migration]]
- [[Resource Reuse]]
- [[VM Sprawl]]
**Prevention:**
- Update the Operating System in the Applications
- Ensure that Each Virtual Machine has a Good Antivirus Solution Installed
- Good Strong Passwords and Good Policies
- Enable encryption of the file that hosts the vm

Are segmented and separated by default

# VM Escape

Occurs when an attacker is able to break out of a locally isolated virtual machine onto the rest of the physical server

# Privilege Elevation

Occurs when a user is able to gain the ability to run functions as a higher level user

# Live VM Migration

When a virtual machine needs to move from one physical host to another

# Resource Reuse

Concept in computing where system resources like memory or processing power are reused

# VM Sprawl

Where VMs are created or deployed without proper oversight, making it easy to lose track of them

# Containerization

Lightweight alternative to full machine virtualization

A method of running applications in isolated user spaces called containers

Thes containers are isolated from each other but share the whole system's OS kernel

Each container contains the application and it's depyendencies, shares OS, binaries, and libraries from host machine
Offers:
- Efficiency
- Speed
- Portability
- Scalability
- Isolation
- Consistency
Examples:
- Docker
- Kubernetes
- Red Hat OpenShift
# Hypervisor Type 1

Known as a bare metal or native hypervisor, it runs directly on the host hardware and functions similarly to an operating system
 Example: Microsoft Hyper-V, Citrix's XenServer, VMware's ESXi, VMware's vSphere

# Hypervisor Type 2

Operates within a standard operating system, such as Windows, Mac, or Linux
    - VirtualBox, VMware