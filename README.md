# Modern Algorithms in the Web Cryptography API

This repository contains a proposal to add support for various
post-quantum secure and modern cryptographic algorithms in the
Web Cryptography API, namely:

- ML-KEM
- ML-DSA
- SLH-DSA
- AES-OCB
- ChaCha20-Poly1305
- SHA-3, cSHAKE and KMAC
- Argon2

Additionally, it proposes to add functions for key encapsulation and decapsulation;
`SubtleCrypto.encapsulateKey`, `SubtleCrypto.encapsulateBits`,
`SubtleCrypto.decapsulateKey` and `SubtleCrypto.decapsulateBits`.

Finally, it proposes to add a `SubtleCrypto.supports` function,
for improved algorithm support detection.

See the [draft specification](https://twiss.github.io/webcrypto-modern-algos/).
