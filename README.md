_This proposal follows the [ARC template for Asset Onboarding](https://docs.aave.com/governance/aip-templates/template-asset-onboarding) laid out in the
Aave Governance documentation._

---

## Sentence Rational

We propose to list THORChain's token RUNE as an asset on Aave.

## References

- [project](https://thorchain.org),

- [whitepaper](https://rebase.foundation/network/thorchain/specification-document-walkthrough/whitepaper),

- [document portal](https://github.com/thorchain/Resources),

- [source code for the system(s) that interact with the proposed asset](https://gitlab.com/thorchain),

- [Ethereum addresses contracts](https://etherscan.io/address/0x3155ba85d5f96b2d030a4966af206230e46849cb),

- ChainLink Oracle – not available,

- [audits both procedural and smart contract focused](https://github.com/thorchain/Resources/tree/master/Audits),

- [communities](https://t.me/thorchain_org)

## Paragraph Summary

RUNE has recently been growing its economic bandwidth on Ethereum. [Myself and other community members](https://twitter.com/tannedoaksprout/status/1355565212972281856) have expressed a desire to be able to use the ERC-20 asset as collateral for lending. Aave is the premier credit facility in crypto, and so here is a listing proposal for the community’s review.

## Motivation

Listing RUNE benefits the Aave community in the following ways:

1. Unique Properties: RUNE has properties which makes it desirable as both a
   collateral and borrow asset (discussed in detail later).
2. First-Mover: RUNE has only recently been made available as an ERC-20 asset, and Aave would be the first venue to make RUNE borrowing available.
3. Community and New Users: The THORChain community is extremely strong, vocal and eager to support related projects. This listing would bring a strong influx of new users.

## Specifications

NB: At this moment, the majority of RUNE is based on Binance Chain as a BEP2
asset. This will soon migrate to a token native to the THORChain. There is also
a significant portion of RUNE bridged to Ethereum as an ERC-20. For the sake of
providing adequate context, I will provide data about the BEP2 asset as well as
the asset in question, ERC-20 RUNE.

### What is the link between the author of the AIP and the Asset?

Oaksprout is a long-term community member of THORChain and holder of RUNE. He has also spent a lot of time in the Aave community and holds AAVE.

### Provide a brief high-level overview of the project and the token

THORChain is a decentralised network focused on bringing liquidity to cross-chain assets. It does this using a simple Uniswap-like automated market maker (AMM) design. Some have called it “Uniswap for the multichain world”.

THORChain has been live with mainnet assets since September 2020 and its flagship multichain network is scheduled to go to testnet imminently.

The project is built on tried-and-tested technical and economic primitives, including Tendermint BFT, Cosmos SDK, Gennaro and Goldfeder’s Threshold Signature Scheme (TSS) and a variant on Uniswap’s constant function market making formula.

### Explain positioning of token in the AAVE ecosystem. Why would it be a good borrow or collateral asset?

RUNE is a unique asset in that it is both a desirable collateral
**and** borrow asset. This is due to 2 main elements of its novel design:

1. strong value accrual design and deterministic price floor – desirable collateral asset
2. RUNE price is tied to the deepest liquidity assets in crypto, and therefore
   market neutral – desirable borrow asset

#### Desirable Collateral Asset

THORChain provides competitive long-term yield for large cap assets, and efficiently converts that
liquidity into RUNE market cap through a unique economic design. All this
amounts to an asset with extremely high upside potential. This is desirable as
collateral as it makes it easier and more efficient to manage collateral postions.

Additionally, THORChain's economic model requires that $3 of RUNE is staked for
every $1 of pooled asset, e.g. BTC. This means that with time, a deterministic
price floor will emerge, i.e. collateral providers will always have a solid
price floor to plan around.

#### Desirable Borrow Asset

RUNE is a desirable borrow asset because of its wide and deep market exposure.
Given that RUNE is the settlement asset of the network, its price volatility is
tied to the liquidity levels and prices of connected assets. THORChain optimises
for sucking in liquidity from the largest cap assets. Given this, RUNE is likely
to become market neutral to the entirety of the crypto market. For this reason,
RUNE stands a good chance of becoming a desirable borrow asset given its
_relative_ stability to the rest of crypto, and to the assets on Aave.

For these reasons I believe RUNE represents unique benefits to the Aave ecosystem.

### Provide a brief history of the project and how it overcame stressed conditions

### How is the asset currently used?

ERC-20 RUNE is predominantly used as a source of liquidity on Sushiswap. There, RUNE is
pooled with ~a dozen major DeFi assets including AAVE.

Recently 10m RUNE was bridged over to Ethereum by the THORChain team to meet
demand. That is mostly still sitting in the deployer contract, waiting to be
used on Ethereum.

See the breakdown below. Note that several of the largest uses of RUNE are on
Sushiswap, but a significant part remains ununused.

![](https://i.imgur.com/YlZOuxr.png)

BEP2 RUNE is roughly 30% deployed, on Binance Chain. See the breakdown below:

![](https://i.imgur.com/nVmSEe1.png)

Source: Delphi Digital THORChain Dashboard

### Emission schedule

Current circulating supply of RUNE is 238,275,761. Total circulating supply will
be 500 million.

Current circulating supply of RUNE in ERC-20 form is 10,075,916. Current maximum
supply on Ethereum is 20 million. This number was recently doubled from
10 million.

Figures sourced from CoinGecko data on [BEP2
RUNE](https://www.coingecko.com/en/coins/thorchain) and [ERC-20
RUNE](https://www.coingecko.com/en/coins/thorchain-erc20). [See further details
on THORChain's](https://governance.aave.com/t/listing-proposal-add-rune-erc-20-thorchain/2239/4?u=oaksprout) ERC-20 version of RUNE.

THORChain rewards early behaviour by giving out RUNE to active participants. It
gives out 1/6 of its reserve each year. THORChain aims to reach 2% annual
inflation after 10 years.

![THORChain Emission Curve Over 10 Years](https://cdn.sanity.io/images/6vy4jhfn/production/74a2ff473174aaa37eb02499abcc656c587584ba-1356x808.png)

### Token permissions and upgradability

### Market data (Market Cap, 24h Volume, Volatility, Exchanges, Maturity)

### Social channels data (Size of communities, activity on Github)

- Gitlab activity – no summary data available – [check Activity page](https://gitlab.com/groups/thorchain/-/activity)
- THORChain Twitter – [36.1k Followers](https://twitter.com/thorchain_org)
- LunarCrush – [65.5](https://lunarcrush.com/coins/rune/thorchain?section=galaxy-score&interval=1%20Year)
- THORChain Telegram – [7,553 members](https://t.me/thorchain_org)

### Contracts date of deployments, number of transactions, number of holders for tokens

- Token contract deployed Jan-13-2021 04:17:27 AM +UTC – [Transaction](https://etherscan.io/tx/0xcb1088b48bca2aaf34e51c9a3629153762bda0cee4b0154464830e1a79f2f16f)
- Total transactions at 15 Feb 10:26 UTC – [21,067](https://etherscan.io/token/0x3155ba85d5f96b2d030a4966af206230e46849cb)
- Token Holders at 15 Feb 10:26 UTC – [1,955](https://etherscan.io/token/0x3155ba85d5f96b2d030a4966af206230e46849cb#balances)

## Technical Specifications

## Security Considerations

The RUNE token doesn’t have any specific behaviour (eg. rebasing, balance increasing) and doesn’t offer meta governance functionality. Therefore, the standard AToken contract and corresponding debt tokens, already used for the majority of assets listed in Aave, can be also used for RUNE. No auditing of the code is required.

---

## Questions

- what is required in the "Token permissions and upgradability" section?
-
