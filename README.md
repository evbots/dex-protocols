# Protocols for Decentralized Exchange
These are protocols for exchanging a wide variety of cryptographic assets on a blockchain. All of these protocols implement their feature set via smart contracts.

| Protocol  | Asset(s) | Blockchain(s) | Status | Notes |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| [0x](https://www.0xproject.com/)  | ERC20 Tokens  | Ethereum | Live on Ethereum mainnet | Generic exchange of ERC20 |
| [Bitshares](https://bitshares.org/) | All[3] | Bitshares | Live on Bitshares mainnet | Bitshares is a company that created a dex on top of their blockchain. This is a closed protocol.
| [Dharma](https://dharma.io/) | ERC20 Tokens, Dharma Debt Token | Ethereum | Under development | Debt contracts |
| [Dydx](https://dydx.exchange/) | ERC20 Tokens, Dydx Derivatives (Option, Short Sell) | Ethereum | Under development | Derivatives contracts, uses 0x |
| [Enigma](https://www.enigma.co/) | All[2] | All[2] | Proposed | The Engima team is working on many projects. A protocol for decentralized exchanged was proposed in one of their papers. |
| [Lendroid](https://lendroid.com/) | ERC20 Tokens | Ethereum | Under development | Margin Loans |
| [OmiseGo](https://omisego.network/) | All[1] | All[1] | Under development | A blockchain with built-in support for decentralized exchange |
| [Set](https://setprotocol.com/) | ERC20 Tokens, Set Tokens | Ethereum | Under development | Token abstraction |
| [Snowglobe](https://auroradao.com/faq/) | ERC20 Tokens | Ethereum | Under development | Shared order book and liquidity |
| [Swap](https://swap.tech/faq/)  | ERC20 Tokens  | Ethereum | Under development | Closed protocol with plans to be open |

---
[1] The OmiseGo white paper claims to support generic exchange between any blockchain-based cryptocurrency.

[2] The Enigma Catalyst [white paper](https://www.enigma.co/enigma_catalyst.pdf) proposes an architecture for cross-chain atomic swaps using layer 2 solutions (also known as state channels). As far as I can tell, this is not currently being developed by the Enigma team.

[3] Bitshares claims that you can trade collateralized smartcoins (analogous to Ethereum ERC20 stablecoins). Bitshares claims to hold the collateral for these coins.
