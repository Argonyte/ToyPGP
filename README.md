# Toy PGP

PGP (Pretty Good Privacy) is a software protocol that enables people to securely exchange information by encrypting, decrypting, and digitally signing data. PGP combines multiple cryptographic methods:

- Public-key cryptography: Each user has a public key (shared) and a private key (kept secret). Messages encrypted with the public key can only be decrypted with the private key, ensuring only the intended recipient can read the message
 -   Symmetric-key cryptography: Once a shared secret (session key) is established, symmetric encryption is used for fast data encryption and decryption.
 -   Hashing and digital signatures: PGP can create a hash of a message and sign it with the sender’s private key. This allows the recipient to verify the authenticity and integrity of the message using the public key.

PGP is widely used to secure email and file communications against unauthorized access and tampering. The protocol follows the OpenPGP standard (RFC 4880), and is interoperable with tools like GnuPG (Source: Fortinet)

---

This is just a Proof of Concept our team made for our course work for Introduction to Programming and Algorithms for our program in Masters in Finance
