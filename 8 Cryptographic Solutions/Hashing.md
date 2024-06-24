# Hashing

One-way cryptographic function that takes an input and produces a unique message digest as its output
- Hash digests are always the same length

- Different Hashing Algorithms:
  1. [[MD5 (Message Digest Algorithm 5)]]
  2. Secure Hash Algorithm Family (SHA)
    - [[SHA-1]]
    - [[SHA-2]]
    - [[SHA-3]]
  3. [[RIPEMD (RACE Integerity Primitive Evaluation Message Digest)]]
    - [[RIPEMD-160]]
  4. [[HMAC (Hash-based Message Authentication Code)]]
- [[Digital Signature]]
  - Digital Signature encryption angorithms:
    - [[Digital Security Algorithm (DSA)]]
    - [[RSA (Ron RIvest, Adi Shamir, and Leonard Adleman)]]

# MD5 (Message Digest Algorithm 5)
Creates a 128-bit hash value that is unique to the input file

# SHA-1

Creates a 160-bit hash digest, which significantly reduces the number of collisions that occur

# SHA-2

Family of hash functions that contains longer hash digests

- @SHA-224
- @SHA-256
- @SHA-384
- @SHA-512

64-80 computations to create its message digest

# SHA-3

Newer family of hash functions and its hash digest can go between 224 bits and 512,

uses 120 rounds of computations to create its message digest to create each file

# RIPEMD (RACE Integerity Primitive Evaluation Message Digest)

Comes in 160-bit, 256-bit, and 320-bit versions

# RIPEMD-160
Open-Source Hashing Algorithm that was created as a competitor to the SHA family

# HMAC (Hash-based Message Authentication Code)

Used to check the integrity of a message and provides some level of assurance that its authenticity is real
    - @HMAC-MD5
    - @HMAC-SHA1
    - @HMAC-SHA256
  
# Digital Security Algorithm (DSA)

# Digital Security Standard (DSS)

Used by the federal government
Relies upon a 160-bit message digest created by the [[Digital Security Algorithm (DSA)]]

- Commerial services uses [[RSA (Ron RIvest, Adi Shamir, and Leonard Adleman)]]

# Code Signing

Application file will be hashed and that hash will be encrypted using the developer's private key. Ensure the installer wont be modified or corrupted since the developer uploaded the file.

