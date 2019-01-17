# VIPs [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaporyco/VIPs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
Vapory Improvement Proposals (VIPs) describe standards for the Vapory platform, including core protocol specifications, client APIs, and contract standards.

# Contributing
First review [VIP-1](VIPS/vip-1.md). Then clone the repository and add your VIP to it. There is a [template VIP here](vip-X.md). Then submit a Pull Request to Vapory's [VIPs repository](https://github.com/vaporyco/VIPs).

# VIP status terms
* **Draft** - an VIP that is open for consideration
* **Accepted** - an VIP that is planned for immediate adoption, i.e. expected to be included in the next hard fork (for Core/Consensus layer VIPs).
* **Final** - an VIP that has been adopted in a previous hard fork (for Core/Consensus layer VIPs).
* **Deferred** - an VIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.

# Non-final VIPs
| Number                    | Title                                                   | Author                        | Layer     | Status     |
| ------------------------- | ------------------------------------------------------- | ----------------------------- | --------- | ---------- |
| [3](VIPS/vip-3.mediawiki) |  Addition of CALLDEPTH opcode                           | Martin Holst Swende           | Core      | Draft      |
| [4](VIPS/vip-4.mediawiki) |  VIP Classification                                     | Eric Lombrozo                 | Meta      | Draft      |
| [5](VIPS/vip-5.md)        |  Gas Usage for `RETURN` and `CALL*`                     | Christian Reitwiessner        | Core      | Draft      |
| [101](VIPS/vip-101.md)    |  Serenity Currency and Crypto Abstraction               | Vitalik Buterin               |           | Active     |
| [158](VIPS/vip-158.md)    |  State clearing                                         | Vitalik Buterin               | Core      | Superseded |
| [234](VIPS/vip-234.md)    |  Add `blockHash` to JSON-RPC filter options             | Micah Zoltu                   | Interface | Draft      |
| [615](VIPS/vip-615.md)    |  Subroutines and Static Jumps for the EVM               | Greg Colvin                   | Core      | Draft      |
| [616](VIPS/vip-VIPS/vip-616.md)    |  SIMD Operations for the EVM                            | Greg Colvin                   | Core      | Draft      |
| [758](VIPS/vip-758.md)    |  Subscriptions and filters for transaction return data  | Jack Peterson                 | Interface | Draft      |
| [801](VIPS/vip-801.md)    |  ERC-801 Canary Standard                                | ligi                          | Interface | Draft      |

# Deferred VIPs
| Number                                             | Title                                                                                        | Author                                     | Layer      | Status   |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------ | ---------- | -------- |
| [86](https://github.com/vaporyco/VIPs/pull/208)    | Abstraction of transaction origin and signature                                              | Vitalik Buterin                            | Core       | Deferred |
| [96](https://github.com/vaporyco/VIPs/pull/210)    | Blockhash refactoring                                                                        | Vitalik Buterin                            | Core       | Deferred |
| [145](VIPS/vip-145.md)                             | Bitwise shifting instructions in EVM                                                         | Alex Beregszaszi, Paweł Bylica             | Core       | Deferred |

# Finalized VIPs (standards that have been adopted)
| Number                                             | Title                                                                                        | Author                                     | Layer      | Status   |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------| ---------- | -------- |
| [1](VIPS/vip-1.md)                                 | VIP Purpose and Guidelines                                                                  | Martin Becze, Hudson Jameson               | Meta       | Final    |
| [2](VIPS/vip-2.md)                                 | Homestead Hard-fork Changes                                                                  | Vitalik Buterin                            | Core       | Final    |
| [6](VIPS/vip-6.md)                                 | Renaming Suicide Opcode                                                                      | Hudson Jameson                             | Interface  | Final    |
| [7](VIPS/vip-7.md)                                 | DELEGATECALL                                                                                 | Vitalik Buterin                            | Core       | Final    |
| [8](VIPS/vip-8.md)                                 | devp2p Forward Compatibility Requirements for Homestead                                      | Felix Lange                                | Networking | Final    |
| [20](VIPS/vip-20-token-standard.md)                | ERC-20 Token Standard                                                                        | Fabian Vogelsteller, Vitalik Buterin       | ERC        | Final    |
| [55](VIPS/vip-55.md)                               | ERC-55 Mixed-case checksum address encoding                                                  | Vitalik Buterin                            | ERC        | Final    |
| [100](https://github.com/vaporyco/VIPs/issues/100) | Change difficulty adjustment to target mean block time including uncles                      | Vitalik Buterin                            | Core       | Final    |
| [137](VIPS/vip-137.md)                             | Vapory Domain Name Service - Specification                                                 | Nick Johnson                               | ERC        | Final    |
| [140](https://github.com/vaporyco/VIPs/pull/206)   | REVERT instruction                                                                           | Alex Beregszaszi, Nikolai Mushegian        | Core       | Final    |
| [141](VIPS/vip-141.md)                             | Designated invalid EVM instruction                                                           | Alex Beregszaszi                           | Core       | Final    |
| [150](VIPS/vip-150.md)                             | Gas cost changes for IO-heavy operations                                                     | Vitalik Buterin                            | Core       | Final    |
| [155](VIPS/vip-155.md)                             | Simple replay attack protection                                                              | Vitalik Buterin                            | Core       | Final    |
| [160](VIPS/vip-160.md)                             | EXP cost increase                                                                            | Vitalik Buterin                            | Core       | Final    |
| [161](VIPS/vip-161.md)                             | State trie clearing (invariant-preserving alternative)                                       | Gavin Wood                                 | Core       | Final    |
| [162](VIPS/vip-162.md)                             | ERC-162 ENS support for reverse resolution of Vapory addresses                             | Maurelian, Nick Johnson                    | ERC        | Final    |
| [170](VIPS/vip-170.md)                             | Contract code size limit                                                                     | Vitalik Buterin                            | Core       | Final    |
| [181](VIPS/vip-181.md)                             | ERC-181 ENS support for reverse resolution of Vapory addresses                             | Nick Johnson                               | ERC        | Final    |
| [190](VIPS/vip-190.md)                             | ERC-190 Vapory Smart Contract Packaging Standard                                           | Merriam, Coulter, Erfurt, Catalano, Matias | ERC        | Final    |
| [196](https://github.com/vaporyco/VIPs/pull/213)   | Precompiled contracts for addition and scalar multiplication on the elliptic curve alt_bn128 | Christian Reitwiessner                     | Core       | Final    |
| [197](https://github.com/vaporyco/VIPs/pull/212)   | Precompiled contracts for optimal Ate pairing check on the elliptic curve alt_bn128          | Vitalik Buterin, Christian Reitwiessner    | Core       | Final    |
| [198](https://github.com/vaporyco/VIPs/pull/198)   | Precompiled contract for bigint modular exponentiation                                       | Vitalik Buterin                            | Core       | Final    |
| [211](https://github.com/vaporyco/VIPs/pull/211)   | New opcodes: RETURNDATASIZE and RETURNDATACOPY                                               | Christian Reitwiessner                     | Core       | Final    |
| [214](https://github.com/vaporyco/VIPs/pull/214)   | New opcode STATICCALL                                                                        | Vitalik Buterin, Christian Reitwiessner    | Core       | Final    |
| [649](https://github.com/vaporyco/VIPs/pull/669)   | Metropolis Difficulty Bomb Delay and Block Reward Reduction                                  | Afri Schoedon, Vitalik Buterin             | Core       | Final    |
| [658](https://github.com/vaporyco/VIPs/pull/658)   | Embedding transaction status code in receipts                                                | Nick Johnson                               | Core       | Final    |
| [706](VIPS/vip-706.md)                             | DEVp2p snappy compression                                                                    | Péter Szilágyi                             | Networking | Final    |

# Past Hard Forks
| Codename                              | Aliases                     | Block number   | Date (UTC) |
|-------------------------------------- |---------------------------- |----------------|------------|
| [Homestead](VIPS/vip-606.md)          |                             | 1,150,000      | 2016-03-14 |
| [DAO Fork](VIPS/vip-779.md)           |                             | 1,920,000      | 2016-07-20 |
| [Tangerine Whistle](VIPS/vip-608.md)  | Anti-DoS, VIP 150           | 2,463,000      | 2016-10-18 |
| [Spurious Dragon](VIPS/vip-607.md)    | State-clearing, VIP 158/161 | 2,675,000      | 2016-11-22 |
| [Byzantium](VIPS/vip-609.md)          | Metropolis: Part 1          | 4,730,000      | 2017-10-16 |
