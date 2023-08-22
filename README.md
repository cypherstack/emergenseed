# Emergenseed

This repository houses the technical note describing **Emergenseed**, a protocol designed for the safe use of memorized digital asset mnemonics for temporary high-risk environments.

Emergenseed trades the risk of failed mnemonic memorization away in favor of lower (but known) initial entropy.
It adds a high-complexity password-based key derivation in order to mitigate brute-force attacks, and is specifically intended only for temporary use where this mitigation may be of sufficient security.

The design of Emergenseed is by [Cypher Stack](https://cypherstack.com/).

## Warnings

Here are important warnings:
- The design of Emergenseed is **experimental**. It has undergone no external formal review, may be unsafe, and is not yet suitable for production. Use it only for research purposes.
- Emergenseed was built for **limited and specific threat models** and is specifically not suitable for long-term use. Do not use it as such.
