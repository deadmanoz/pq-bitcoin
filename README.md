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
- 2017-11-27 - Fortune (Web Archive): [Nearly 4 Million Bitcoins Lost Forever, New Study Says](https://web.archive.org/web/20220628015523/https://fortune.com/2017/11/25/lost-bitcoins/)
- 2018-05-29 - Unchained: [Bitcoin Data Science (Pt. 2): The Geology of Lost Coins](https://www.unchained.com/blog/geology-of-lost-coins)
- 2025-01-15 - Cointelegraph: [Bitcoin vs. the quantum computer threat: Timeline and solutions (2025–2035)](https://cointelegraph.com/magazine/bitcoin-quantum-computer-threat-timeline-solutions-2024-2035/)
- 2025-03-16 - Jameson Lopp: [Against Allowing Quantum Recovery of Bitcoin](https://blog.lopp.net/against-quantum-recovery-of-bitcoin/)

### High-level
- (2022) McKinsey: [When - and how - to prepare for post-quantum cryptography](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/when-and-how-to-prepare-for-post-quantum-cryptography)
- (2023) RAND: [When a Quantum Computer Is Able to Break Our Encryption, It Won't Be a Secret](https://www.rand.org/pubs/commentary/2023/09/when-a-quantum-computer-is-able-to-break-our-encryption.html)
- (2024) [Chinese researchers break RSA encryption with a quantum computer](https://www.csoonline.com/article/3562701/chinese-researchers-break-rsa-encryption-with-a-quantum-computer.html)

### Technical
- (2020) StackExchange: [Could Taproot create larger security risks or even hinder future protocol adjustments re: Quantum threats?](https://bitcoin.stackexchange.com/questions/93047/could-taproot-create-larger-security-risks-or-even-hinder-future-protocol-adjust)
- (2020) StackExchange: [Is it possible to mine Bitcoin by implementing Grovers algorithm on a quantum computer?](https://quantumcomputing.stackexchange.com/questions/9798/is-it-possible-to-mine-bitcoin-by-implementing-grovers-algorithm-on-a-quantum-c/12847#12847)
- (2021) OpTech #141: [Discussion of quantum computer attacks on taproot](https://bitcoinops.org/en/newsletters/2021/03/24/#discussion-of-quantum-computer-attacks-on-taproot)
- (2024) [Hash-Based Signature Schemes for Post-Quantum Bitcoin](https://conduition.io/cryptography/quantum-hbs/)
- (2024) [Quantum Securing Bitcoin Really Isn’t That Hard](https://blog.coinshares.com/quantum-securing-bitcoin-really-isnt-that-hard-250d16157cb9)
- (2024) MARA: [Bitcoin vs. Quantum Computing: More Hype Than Reality](https://www.mara.com/posts/bitcoin-vs-quantum-computing-more-hype-than-reality)
- (2025) River: [Will Quantum Computing Break Bitcoin?](https://river.com/learn/will-quantum-computing-break-bitcoin/)

## Discussions
Discussions relating to quantum computing and Bitcoin on the [Bitcoin Development Mailing List (BDML)](https://groups.google.com/g/bitcoindev), [Delving Bitcoin (DB)](https://delvingbitcoin.org/), and [BitcoinTalk (BT)](https://bitcointalk.org/).

- (2024) DB: [Proposing a P2QRH BIP towards a quantum resistant soft fork](https://delvingbitcoin.org/t/proposing-a-p2qrh-bip-towards-a-quantum-resistant-soft-fork/956?u=cryptoquick)
- (2024) BDML: [Proposing a P2QRH BIP towards a quantum resistant soft fork](https://groups.google.com/g/bitcoindev/c/Aee8xKuIC2s)
- (2024) BDML: [Trivial QC signatures with clean upgrade path](https://groups.google.com/g/bitcoindev/c/8O857bRSVV8)
- (2024) BDML: [Proposal for Quantum-Resistant Cryptography in Bitcoin - BIP Submission](https://groups.google.com/g/bitcoindev/c/p8xz08YTvkw)
- (2025) BDML: [Proposal for Quantum-Resistant Address Migration Protocol (QRAMP) BIP](https://groups.google.com/g/bitcoindev/c/8PM6iZCeDMc)
- (2025) BDML: [Against Allowing Quantum Recovery of Bitcoin](https://groups.google.com/g/bitcoindev/c/uUK6py0Yjq0)
- (2025) BDML: [Hashed keys are actually fully quantum secure](https://groups.google.com/g/bitcoindev/c/jr1QO95k6Uc)

## Projects
- [Project 11](https://www.projecteleven.com/)
- [The QDay Prize - Can you break ECC with Quantum?](https://www.qdayprize.org/)

## Industry adoption
Not related to Bitcoin perse, but highlighting some industry adoption of post-quantum cryptography.
- 2022-10-03 - Cloudflare: [Defending against future threats: Cloudflare goes post-quantum](https://blog.cloudflare.com/post-quantum-for-all/)
- 2023-08-10 - Google: [Protecting Chrome Traffic with Hybrid Kyber KEM](https://blog.chromium.org/2023/08/protecting-chrome-traffic-with-hybrid.html)
- 2023-09-19 - Signal: [Quantum Resistance and the Signal Protocol](https://signal.org/blog/pqxdh/)
- 2023-09-29 - Cloudflare: [Cloudflare now uses post-quantum cryptography to talk to your origin server](https://blog.cloudflare.com/post-quantum-to-origins/)
- 2024-02-21 - Apple: [iMessage with PQ3: The new state of the art in quantum-secure messaging at scale](https://security.apple.com/blog/imessage-pq3/)

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
