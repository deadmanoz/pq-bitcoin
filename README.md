# Post-Quantum Bitcoin
A collection of information about the quantum computing (QC) threat to Bitcoin, including articles, websites, academic papers, and other resources.

# Papers
A non-exhaustive list of papers that are relevant to the topic of QC and Bitcoin.
I link to my personal notes on each paper (coming soon).
Sorted by year of publication, to be alternatively sorted by topic/tag at a later date.

## QC Foundations
- Shor's algorithm: (1994) [Polynomial-Time Algorithms for Prime Factorization and Discrete Logarithms on a Quantum Computer](https://arxiv.org/abs/quant-ph/9508027v2)
- Grover's algorithm: (1996) [A fast quantum mechanical algorithm for database search](https://arxiv.org/abs/quant-ph/9605043)

## QC & Bitcoin
- (2016) [Estimating the cost of generic quantum pre-image attacks on SHA-2 and SHA-3](https://eprint.iacr.org/2016/992)
- (2017) [Quantum attacks on Bitcoin, and how to protect against them](https://arxiv.org/abs/1710.10377)
- (2017) [Bitcoin and quantum computing](https://arxiv.org/abs/1711.04235)
- (2018) [On the insecurity of quantum Bitcoin mining](https://arxiv.org/abs/1804.08118)
- (2018) [Committing to Quantum Resistance: A Slow Defence for Bitcoin against a Fast Quantum Computing Attack](https://eprint.iacr.org/2018/213)
- (2021) [Assessment of Quantum Threat To Bitcoin and Derived Cryptocurrencies](https://eprint.iacr.org/2021/967)
- (2021) [Conditions for Advantageous Quantum Bitcoin Mining](https://arxiv.org/abs/2110.00878)
- (2022) [The impact of hardware specifications on reaching quantum advantage in the fault tolerant regime](https://pubs.aip.org/avs/aqs/article/4/1/013801/2835275/The-impact-of-hardware-specifications-on-reaching)
- (2022) [Quantum Bitcoin Mining](https://pmc.ncbi.nlm.nih.gov/articles/PMC8946996/)
- (2022) [The Superlinearity Problem in Post-Quantum Blockchains](https://eprint.iacr.org/2022/1423)
- (2023) [Making Classical (Threshold) Signatures Post-Quantum for Single Use on a Public Ledger](https://eprint.iacr.org/2023/420)
- (2023) [How to compute a 256-bit elliptic curve private key with only 50 million Toffoli gates](https://arxiv.org/abs/2306.08585)
- (2024) [51% Attack via difficulty increase with a small quantum miner](https://arxiv.org/abs/2403.08023)
- (2024) [Downtime Required for Bitcoin Quantum-Safety](https://arxiv.org/abs/2410.16965)
- (2025) [From portfolio optimization to quantum blockchain and security: a systematic review of quantum computing in finance](https://jfin-swufe.springeropen.com/articles/10.1186/s40854-025-00751-6)

# Articles / Webpages / Projects
A non-exhaustive list of articles, webpages, and projects that are relevant to the topic of QC and Bitcoin.
Also includes links to adjacent topics such as the post-quantum efforts of some other cryptocurrencies and tech industry adoption.

## Articles


## Projects
- [Project 11](https://www.projecteleven.com/)
- [The QDay Prize - Can you break ECC with Quantum?](https://www.qdayprize.org/)

## Industry adoption
Not related to Bitcoin perse, but highlighting some industry adoption of post-quantum cryptography.
- 2022-10-03 - Cloudflare - [Defending against future threats: Cloudflare goes post-quantum](https://blog.cloudflare.com/post-quantum-for-all/)
- 2023-08-10 - Google - [Protecting Chrome Traffic with Hybrid Kyber KEM](https://blog.chromium.org/2023/08/protecting-chrome-traffic-with-hybrid.html)
- 2023-09-19 - Signal - [Quantum Resistance and the Signal Protocol](https://signal.org/blog/pqxdh/)
- 2023-09-29 - Cloudflare - [Cloudflare now uses post-quantum cryptography to talk to your origin server](https://blog.cloudflare.com/post-quantum-to-origins/)
- 2024-02-21 - Apple - [iMessage with PQ3: The new state of the art in quantum-secure messaging at scale](https://security.apple.com/blog/imessage-pq3/)

# Bitcoin Improvement Proposals
BIPs relating to quantum computing, whether they have been accepted to the official [bitcoin/bips](https://github.com/bitcoin/bips) repository or not.

## QuBit - Pay to Quantum Resistant Hash (P2QRH)

> This document proposes the introduction of a new output type using signatures based on Post-Quantum Cryptography (PQC).
>
> This approach for adding a post-quantum secure output type does not require a hard fork or block size increase.

- https://github.com/bitcoin/bips/pull/1670
- Author: [cryptoquick](https://github.com/cryptoquick) (Hunter Beast)
- Status: Official (pull request)

Related:
- [Bitcoin Development Mailing List: Proposing a P2QRH BIP towards a quantum resistant soft fork](https://groups.google.com/g/bitcoindev/c/Aee8xKuIC2s)

## Hourglass spending rules

>This BIP describes a new set of spending rules for Bitcoin called "Hourglass." The intent is to impose a throughput restriction on the number of P2PK spends to one per block-- to slow the inflationary impacts of potential quantum attacks on these addresses.

- https://github.com/cryptoquick/bips/blob/hourglass/bip-hourglass.mediawiki
- Author: [cryptoquick](https://github.com/cryptoquick) (Hunter Beast)
- Status: Unofficial (fork)

Related:
- [Bitcoin Development Mailing List: Introducing Hourglass](https://groups.google.com/g/bitcoindev/c/zmg3U117aNc)

## Pay to Taproot Hash (P2TRH)

> This BIP proposes a new Segregated Witness output type called Pay to Taproot Hash (P2TRH). It is structurally similar to Pay to Taproot (BIP-341) but replaces the "X-only" public key commitment in the output script with a HASH256 commitment of that public key. The actual public key is only revealed in the witness at spending time, reducing its long-term on-chain exposure to potential quantum-based attacks.
>
>This approach is not a fully quantum-safe solution using Post-Quantum Cryptography (PQC). For that, see BIP-360. Rather, it is a conservative _intermediary_ measure: it defers key disclosure until spend time, potentially reducing attack vectors reliant on indefinite on-chain exposure of elliptic curve public keys.

- https://github.com/cryptoquick/bips/blob/p2trh/bip-p2trh.mediawiki
- Author: [cryptoquick](https://github.com/cryptoquick) (Hunter Beast)
- Status: Unofficial (fork)

Related:
- [Bitcoin Development Mailing List: P2QRH / BIP-360 Update](https://groups.google.com/g/bitcoindev/c/oQKezDOc4us)
