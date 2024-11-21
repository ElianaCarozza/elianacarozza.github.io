---
title: "Faster Signatures from MPC-in-the-Head"
collection: publications
permalink: /publication/2024-252
date: 2024-08-30
published_at: 'ePrint'
paperurl: 'https://eprint.iacr.org/2024/252.pdf'
presented_at: 'Asiacrypt 2024'
excerpt: 'This paper revisits the construction of signature schemes using the MPC-in-the-head paradigm, contributing two key results. First, it is noted that previous schemes relying on this paradigm require a salted version of the GGM puncturable pseudorandom function (PPRF) to prevent collision attacks. A new, efficient PPRF construction is introduced, which is provably secure in the multi-instance setting. The security analysis, performed in the ideal cipher model, forms a core technical contribution. Unlike earlier constructions that depended on a hash function, this approach uses only a fixed-key block cipher, resulting in a 12× to 55× efficiency improvement over recent schemes like Joux and Huth (Crypto’24). This improved PPRF can accelerate various MPC-in-the-head signature schemes.
Additionally, a new signature scheme is introduced based on the regular syndrome decoding assumption. It employs a new protocol for the MPC-in-the-head paradigm, significantly reducing communication overhead compared to previous work. The scheme is conceptually straightforward, though its security analysis involves a complex combinatorial analysis.'
---

