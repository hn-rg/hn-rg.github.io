---
icon: fa-solid fa-person
permalink: /projects/BitMLx/
title: BitMLx
type: project
order: 0 # Technical reasons
---

In this project, we explore the possibility of extending the [BitML](https://eprint.iacr.org/2018/122.pdf) language to a synchronous cross-blockchain setting.

## Abstract
The limited scripting capabilities in Bitcoin-like cryptocurrencies have forced implementations of smart contracts as multi-party cryptographic protocols. To streamline this process, the BitML language allows for defining simple smart contracts and automatically translates them into protocols over transactions in the respective currency. However, BitML is limited to contracts operating upon the same cryptocurrency whereas many interesting financial applications involve assets on different blockchains, inducing more complicated cryptographic protocols for enforcing synchronous execution across these systems. In this work, we introduce BitMLx, an extension of BitML that provides a high-level programming language to implement smart contracts executing synchronously on any two Bitcoin-like cryptocurrencies. We provide a compiler from BitMLx to two BitML contracts and formally prove that participants executing the latter contracts end up at least as good as in the corresponding execution of the former BitMLx contract. 

## Dowloads

FCS 2023 [short paper](../../downloads/BitMLx-137.pdf) and [slides](../../downloads/BitMLx_slides_FCS23.pdf).

Compiler PoC [in GitHub](https://github.com/hn-rg/BitMLx).
