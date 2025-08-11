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

To accommodate the usage of ML-KEM, and possibly future other KEMs,
it proposes to add functions for key encapsulation and decapsulation;
`SubtleCrypto.encapsulateKey`, `SubtleCrypto.encapsulateBits`,
`SubtleCrypto.decapsulateKey` and `SubtleCrypto.decapsulateBits`.

Additionally, it proposes to add a `SubtleCrypto.getPublicKey` function,
to be able to derive a public key from its corresponding private key,
and a `SubtleCrypto.supports` function, for improved algorithm support
detection.

See the [draft specification](https://wicg.github.io/webcrypto-modern-algos/).
