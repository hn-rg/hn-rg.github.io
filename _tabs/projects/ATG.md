---
icon: fa-solid fa-person
permalink: /projects/ATG/
title: Atomic Transfer Graphs: Secure-by-design Protocols for Heterogeneous Blockchain Ecosystems
type: project
order: 0 # Technical reasons
---

In this project we developed a secure-by-design framework for multi-party asset swaps across heterogeneous Blockchain Ecosystems. 

## Abstract
The heterogeneity of the blockchain landscape has
motivated the design of blockchain protocols tailored to specific
blockchains and applications that, hence, require custom security
proofs. We observe that many blockchain protocols share common security and functionality goals, which can be captured by
an atomic transfer graph (ATG) describing the structure of desired
transfers. Based on this observation, we contribute a framework
for generating secure-by-design protocols that realize these goals.
The resulting protocols build upon Conditional Timelock Contracts (CTLCs), a novel minimal smart contract functionality
that can be implemented in a large variety of cryptocurrencies
with a restricted scripting language (e.g., Bitcoin), and payment
channels. We show how ATGs, in addition to enabling novel
applications, capture the security and functionality goals of
existing applications, including many examples from payment
channel networks and complex multi-party cross-currency swaps
among Ethereum-style cryptocurrencies. Our framework is the
first to provide generic and provably secure protocols for all
these use cases while matching or improving the performance of
existing use-case-specific protocols.

## Publications
- [Research Paper](https://www.computer.org/csdl/proceedings-article/csf/2025/108100a016/26w6qFVNMfS) presented at [CSF 2025](https://csf2025.ieee-security.org/) in Santa Cruz, CA, USA
- [Short version](https://hn-rg.github.io/FCS_2023_Workshop.pdf) presented at [FCS 2023](https://squera.github.io/fcs23/) in Dubrovnik, Croatia
- [Extended Version](https://arxiv.org/abs/2501.17786) including all technical details on arXiv 

## Implementation Code
Now at <a href="https://github.com/hn-rg/CTLC-Implementation" target="_blank">GitHub</a>!

### Citation
```
@inproceedings{duebler2024atomictransfergraphs,
  title={Atomic Transfer Graphs: Secure-by-design Protocols for Heterogeneous Blockchain Ecosystems},
  author={Dübler, Stephan and Badaloni, Federico and Moreno-Sanchez, Pedro and Schneidewind, Clara},
  booktitle={2025 IEEE 38th Computer Security Foundations Symposium (CSF)},
  pages={},
  year={2025},
  organization={IEEE Computer Society}
}
```





