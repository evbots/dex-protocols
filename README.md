# Protocols for Decentralized Exchange
This is a list of protocols for peer-to-peer exchange of cryptographic assets. The architecture of these protocols can be quite different from one another. In some cases, they are built as smart contracts that anyone can use. In other cases, they are closed, but still implemented as smart contracts that are publicly verifiable and auditable. Other projects have chosen to create their own blockchain in order to build a protocol for exchange. The approach to liquidity varies as well. Some protocols, like Bancor, have built-in logic for counterparties to find each other. Other protocols, such as 0x, architected the protocol to allow for off-chain liquidity pools, meaning counterparty discovery happens off-chain.

For our purposes, DEX is short for Decentralized Exchange.

| Protocol  | Asset(s) | Blockchain(s) | Status | Notes |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| [0x](https://www.0xproject.com/)  | ERC20 Tokens  | Ethereum | Live on Ethereum mainnet | Open protocol. Generic exchange of ERC20 with off-chain relayers. |
| [Aqueduct](https://aqueduct.ercdex.com)  | ERC20 Tokens  | Ethereum | Live on Ethereum mainnet | Open protocol. |
| [Bancor](https://www.bancor.network/) | ERC20 Tokens | Ethereum | Live on Ethereum mainnet | Open protocol. On-chain exchange and pricing. |
| [Bitshares](https://bitshares.org/) | Bitshares, Bitshares SmartCoins[3] | Bitshares | Live on Bitshares mainnet | Open protocol. Bitshares created a DEX on top of their blockchain. Other DEX's for Bitshares also exist. |
| [CDX](https://github.com/YouDex/cdx) | All | Ethereum, Youdex Sidechain | Proposed | Open protocol. Coin direct exchange, cross-chain atomic swap. |
| [COMIT](http://www.comit.network/) | All[2] | All[2]  | Proposed | Open protocol. Off-chain. Utilizes state channels & 3rd party liquidity providers. |
| [Counterparty](https://counterparty.io/) | Bitcoin, Counterparty Tokens | Bitcoin | Live on Bitcoin mainnet | Open protocol. Counterparty extends Bitcoin by adding metadata to Bitcoin transactions. |
| [DEAL](https://aphelion.org/wp.html) | NEO Assets[6] | NEO | Under development | Closed protocol[6]. Implemented as smart contracts on the NEO blockchain. |
| [Dharma](https://dharma.io/) | ERC20 Tokens, Dharma Debt Token | Ethereum | Under development | Open protocol. Debt contracts. |
| [Dydx](https://dydx.exchange/) | ERC20 Tokens, Dydx Derivatives (Option, Short Sell) | Ethereum | Under development | Open protocol. Derivatives contracts, uses 0x. |
| [Enigma](https://www.enigma.co/) | All[2] | All[2] | Proposed | The Engima team is working on many projects. A protocol for decentralized exchanged was proposed in one of their papers. |
| [Exchange Union](https://www.exchangeunion.com/) | All[9] | All[9] | Under development | Open protocol. Off-chain payment/state channels using cross-chain atomic swaps. Decentralized order propagation. |
| [Komodo](https://www.komodoplatform.com/) | N/A | Komodo | Under development | Closed protocol. Leverages cross chain atomic swaps[4]. |
| [Kyber Network](https://kyber.network/) | ERC20 Tokens | Ethereum | Live on Ethereum mainnet | Closed protocol. Kyber is two things: a product for exchanging, and smart contracts used by that exchange. Only Kyber can use the contracts. |
| [Lendroid](https://lendroid.com/) | ERC20 Tokens | Ethereum | Under development | Open protocol. Margin Loans. |
| [MARKET Protocol](https://www.marketprotocol.io/) | Derivatives | Ethereum | Under development | Open protocol. Cross Chain and real world assets. |
| [Melon](https://melonport.com/) | ERC20 Tokens, Melon Fund Shares[5] | Ethereum | Live on Ethereum mainnet | Open protocol. A protocol for creating an investment fund that holds an arbitrary number of underlying ERC20 tokens. |
| [OmiseGo](https://omisego.network/) | All[1] | All[1] | Under development | Open protocol. A blockchain with built-in support for decentralized exchange. |
| [Raiden Network](https://raiden.network/) | ERC20 Tokens | Ethereum | Under development | Off-chain ERC20 token exchange. Similar to Lightning Network for Bitcoin. |
| [Republic](https://republicprotocol.com/) | ERC20 Tokens, Ether, Bitcoin | Ethereum, Bitcoin | Under development | Open protocol.  Trustless cross-chain atomic trading of Ether, ERC20 tokens and Bitcoin pairs |
| [Ripple](https://ripple.com/) | XRP, Ripple Issued Currencies | Ripple | Live on Ripple mainnet | Open protocol. Ripple has builtin transaction types such as `Offer Create`[8] that allow anyone to trustlessly exchange Ripple based assets. |
| [Saturn](https://rados.io/saturn-protocol-saturn-dao-updates-for-radex-and-rados/) | ERC20 Tokens, ERC223 Tokens | Ethereum | Under development | Open protocol. The team building this already built a dex called Radex, that uses a closed protocol. Saturn is a generalization of Radex protocol. |
| [Set](https://setprotocol.com/) | ERC20 Tokens, Set Tokens | Ethereum | Under development | Open protocol. Token abstraction. |
| [Snowglobe](https://auroradao.com/faq/) | ERC20 Tokens | Ethereum | Under development | Open protocol. Shared order book and liquidity. |
| [Stellar](https://www.stellar.org/developers/guides/concepts/exchange.html) | Stellar Assets | Stellar | Live on Stellar mainnet | Open protocol. The Stellar blockchain scripting language has builtins for decentralized exchange[7].  |
| [Swap](https://swap.tech/faq/)  | ERC20 Tokens  | Ethereum | Under development | Closed protocol. Plans to become an open protocol. |
| [WandX](https://www.wandx.co/) | ERC20 Tokens, ERC20 Token Baskets | Ethereum | Under development | Closed protocol. |
| [Wyvern](https://projectwyvern.com/)  | Nonfungible Ethereum assets  | Ethereum | Live on Ethereum mainnet | Open protocol. Generic exchange of nonfungible Ethereum assets with off-chain orderbooks. |

---
[1] The OmiseGo white paper claims “this high-performant distributed network enforces exchange across as-set classes, from fiat-backed issuers to fully decentralized blockchain tokens (ERC-20 style and native cryptocurrencies).”

[2] The Enigma Catalyst [white paper](https://www.enigma.co/enigma_catalyst.pdf) proposes an architecture for cross-chain atomic swaps using layer 2 solutions (also known as state channels). As far as I can tell, this is not currently being developed by the Enigma team.

[3] Bitshares claims that you can trade collateralized SmartCoins on the Bitshares blockchain. Bitshares claims to hold the collateral for these SmartCoins.

[4] https://blog.komodoplatform.com/everything-you-need-to-know-about-atomic-swaps-and-how-komodo-is-advancing-the-technology-cadaec50da7c

[5] Investors send funds to the "fund manager" and then receive a proportional number of the fund's shares in return.

[6] A company called [Aphelion](https://aphelion.org/) is developing this protocol in order to build their own DEX on top of it. I could not determine from the white paper if they are planning to open this protocol up to others or not. It is unclear from the whitepaper just how many assets this protocol will support.

[7] "Manage Offer" is an example of a function native to Stellar's scripting language https://www.stellar.org/developers/guides/concepts/list-of-operations.html#manage-offer

[8] https://ripple.com/build/transactions/#offercreate

[9] [This work-in-progress document](https://github.com/ExchangeUnion/Docs/blob/master/XU-TechnicalPaper.md) outlines the use of payment/state channels with atomic swaps and the decentralized orderbook approach of Exchange Union. All chains with BIP 199 compatible payment channels can be supported directly, others need a HTLC atomic swap implementation via smart contracts or similar.
