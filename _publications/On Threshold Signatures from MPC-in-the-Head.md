---
title: "On Threshold Signatures from MPC-in-the-Head"
collection: publications
permalink: /publication/
date: 2024-11-21
published_at: 'ePrint'
paperurl: https://elianacarozza.github.io/files/Multisignature.pdf
excerpt: |
  We investigate the feasibility of constructing threshold signature schemes from the MPC-in-the-head paradigm. Our work addresses the significant challenge posed by recent impossibility results (Doerner et al., Crypto’24), which establish inherent barriers to efficient thresholdization of such schemes without compromising their security or significantly increasing the signature size.
  We introduce a general methodology to adapt any MPC-in-the-head signature into a threshold-friendly scheme, ensuring that the dependency on the number of users n grows as λ²n + O(1). This represents a substantial improvement over the naive concatenation of independent signatures.
  We present a threshold signature scheme on top of the scheme of (Carozza, Couteau and Joux, EUROCRYPT’23). Our security analysis introduces the notion of Corruptible Existential Unforgeability under Chosen Message Attacks (CEUF-CMA), which formalizes resilience against adversarial control over parts of the randomness.
  Our results provide a new perspective on the trade-offs between efficiency and security in threshold settings, opening pathways for future improvements in post-quantum threshold cryptography.
---

