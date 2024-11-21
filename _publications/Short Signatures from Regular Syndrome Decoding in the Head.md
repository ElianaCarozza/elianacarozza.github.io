---
title: "Short Signatures from Regular Syndrome Decoding in the Head"
collection: publications
permalink: /publication/2023-1035
date: 2023-07-03
published_at: 'ePrint'
paperurl: 'https://eprint.iacr.org/2023/1035.pdf'
presented_at: 'Eurocrypt 2023'
excerpt: 'This paper introduces a new candidate post-quantum digital signature scheme based on the regular syndrome decoding (RSD) assumption, a well-established variant of the syndrome decoding problem. The scheme is built using a 5-round zero-knowledge proof system with the MPC-in-the-head paradigm. A key part of the construction is an efficient MPC protocol in the preprocessing model that verifies the correctness of an RSD instance through a share ring-conversion mechanism.
The technical analysis is non-trivial and involves combinatorial challenges, such as evaluating soundness in a relaxed model where a cheating prover can use a witness close to a regular vector. The paper also provides a detailed overview of existing attacks against RSD.
The resulting signature scheme is competitive with other code-based schemes, with signature sizes ranging from several KB (fast setting, signing in a few milliseconds on a standard laptop) to more compact versions around 15ms for signing.
---
