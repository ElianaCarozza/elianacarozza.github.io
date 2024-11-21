---
title: "On Threshold Signatures from MPC-in-the-Head"
collection: publications
permalink: /publication/
date: 2024-11-21
published_at: 'ePrint'
paperurl: 
presented_at: 
excerpt: >
  We investigate the feasibility of constructing threshold signature schemes from the MPC-in-the-head paradigm. Our work addresses the significant challenge posed by recent impossibility results (Doerner et al., Crypto’24), which establish inherent barriers to efficient thresholdization of such schemes without compromising their security or significantly increasing the signature size.

  - **General Methodology**: We introduce a general methodology to adapt any MPC-in-the-head signature into a threshold-friendly scheme, ensuring that the dependency on the number of users \(n\) grows as \(\lambda^2n + O(1)\), where \(\lambda\) is the security parameter and \(O(1)\) is a scheme-specific constant. This represents a substantial improvement over the naïve concatenation of independent signatures.

  - **Concrete Instantiation**: We present a threshold signature scheme derived from the regular syndrome decoding assumption, leveraging a simplified MPC-in-the-head protocol. Our security analysis introduces the notion of Corruptible Existential Unforgeability under Chosen Message Attacks (CEUF-CMA), which formalizes resilience against adversarial control over parts of the randomness.

  Our results provide a new perspective on the trade-offs between efficiency and security in threshold settings, opening pathways for future improvements in post-quantum threshold cryptography.
---
