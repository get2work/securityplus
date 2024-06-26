# Redundant Array of Independent Disks (RAID)

Combines multiple physical storage devices into a recognized single logical storage device

- [[RAID 0 (Striping)]]
- [[RAID 1 (Mirroring)]]
- [[RAID 5 (Striping with Parity)]]
- [[RAID 6 (Striping with double parity)]]
- [[RAID 10 (Combined advantages of raid 1 and raid 0)]]

- [[Failure-resistant]]
- [[Fault-tolerant]]
- [[Disaster-tolerant]]

# RAID 0 (Striping)

Provides data **striping** across multiple disks to increase performance
 - Faster read and write speeds
 - Does not provide [[Data Redundancy]]

# RAID 1 (Mirroring)

Mirrors data for redundancy accross two drives or SSDs

# RAID 5 (Striping with Parity)

Stripes data with parity, using at least three storage devices

# RAID 6 (Striping with double parity)

Uses data striping across multiple devices with two pieces of parity data

# RAID 10 (Combined advantages of raid 1 and raid 0)

Combines RAID 1 and RAID 0, featuring mirrored arrays in a striped setup

# Failure-resistant

Use of redundant storage to withstand hardware malfunctions without data loss

Raid 1 and raid 10, using mirroring for data redundancy 

# Fault-tolerant

Use of raid 1, 5, 6, and 10 for uninterrupted operation during hardware failures

# Disaster-tolerant

Protects data from catastrophic events