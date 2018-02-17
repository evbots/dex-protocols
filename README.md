# Protocols for Decentralized Exchange
These are protocols for exchanging a wide variety of cryptographic assets on a blockchain. The architecture of these protocols can be quite different from one another. In some cases, protocols are built as smart contracts that anyone can use. In other cases, they are closed protocols, but still implemented as smart contracts that are publicly verifiable. Other protocols have chosen to create their own blockchain in order to build a protocol for exchange.

For our purposes, DEX is short for Decentralized Exchange.

| Protocol  | Asset(s) | Blockchain(s) | Status | Notes |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| [0x](https://www.0xproject.com/)  | ERC20 Tokens  | Ethereum | Live on Ethereum mainnet | Open protocol. Generic exchange of ERC20 with off-chain relayers. |
| [Bancor](https://www.bancor.network/) | ERC20 Tokens | Ethereum | Live on Ethereum mainnet | Open protocol. On-chain exchange and pricing. |
| [Bitshares](https://bitshares.org/) | Bitshares, Bitshares SmartCoins[3] | Bitshares | Live on Bitshares mainnet | Open protocol. Bitshares created a DEX on top of their blockchain. Other DEX's for Bitshares also exist.
| [Dharma](https://dharma.io/) | ERC20 Tokens, Dharma Debt Token | Ethereum | Under development | Open protocol. Debt contracts. |
| [Dydx](https://dydx.exchange/) | ERC20 Tokens, Dydx Derivatives (Option, Short Sell) | Ethereum | Under development | Open protocol. Derivatives contracts, uses 0x. |
| [Enigma](https://www.enigma.co/) | All[2] | All[2] | Proposed | The Engima team is working on many projects. A protocol for decentralized exchanged was proposed in one of their papers. |
| [Komodo](https://www.komodoplatform.com/) | N/A | Komodo | Under development | Closed protocol. Leverages cross chain atomic swaps[4]. |
| [Kyber Network](https://kyber.network/) | ERC20 Tokens | Ethereum | Live on Ethereum mainnet | Closed protocol. Kyber is two things: a product for exchanging, and smart contracts used by that exchange. Only Kyber can use the contracts. |
| [Lendroid](https://lendroid.com/) | ERC20 Tokens | Ethereum | Under development | Open protocol. Margin Loans. |
| [Melon](https://melonport.com/) | ERC20 Tokens, Melon Fund Shares[5] | Ethereum | Live on Ethereum mainnet | Open protocol. A protocol for creating an investment fund that holds an arbitrary number of underlying ERC20 tokens. |
| [OmiseGo](https://omisego.network/) | All[1] | All[1] | Under development | Open protocol. A blockchain with built-in support for decentralized exchange. |
| [Set](https://setprotocol.com/) | ERC20 Tokens, Set Tokens | Ethereum | Under development | Open protocol. Token abstraction. |
| [Snowglobe](https://auroradao.com/faq/) | ERC20 Tokens | Ethereum | Under development | Open protocol. Shared order book and liquidity. |
| [Swap](https://swap.tech/faq/)  | ERC20 Tokens  | Ethereum | Under development | Closed protocol. Plans to become an open protocol. |

---
[1] The OmiseGo white paper claims to support generic exchange between any blockchain-based cryptocurrency.

[2] The Enigma Catalyst [white paper](https://www.enigma.co/enigma_catalyst.pdf) proposes an architecture for cross-chain atomic swaps using layer 2 solutions (also known as state channels). As far as I can tell, this is not currently being developed by the Enigma team.

[3] Bitshares claims that you can trade collateralized SmartCoins on the Bitshares blockchain. Bitshares claims to hold the collateral for these SmartCoins.

[4] https://blog.komodoplatform.com/everything-you-need-to-know-about-atomic-swaps-and-how-komodo-is-advancing-the-technology-cadaec50da7c

[5] Investors send funds to the "fund manager" and then receive a proportional number of the fund's shares in return.
