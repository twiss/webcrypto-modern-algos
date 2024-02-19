# Modern Algorithms in the Web Cryptography API

This repository contains a proposal to add support for various modern
cryptographic algorithms in the Web Cryptography API, namely:

- AES-OCB
- ChaCha20-Poly1305
- SHA-3, cSHAKE and KMAC
- Argon2

Additionally, it proposes to add a `crypto.subtle.supports` function,
for improved algorithm support detection.

See the [draft specification](https://twiss.github.io/webcrypto-modern-algos/).
