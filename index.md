# Stellar Blockchain Liquidity Provider

### Liquidity Pools

![GitHub Logo](/images/joined.svg)

[A reference codebase to serve as a proof of concept for an AMM UI](https://github.com/stellar/amm-reference-ui)


Connect your app to [Stellar Liquidity Pools](https://developers.stellar.org/api/resources/liquiditypools/)

Liquidity Pools work on Stellar `test network`

On Wed Nov 03 2021 at 17:00:00 GMT+0200 (Eastern European Standard Time) validators will vote on whether to upgrade to Stellar protocol 18.

If the vote goes through, the network upgrade is immediate, builders can connect they apps to `public network` and user can start to use them.


```js
List Liquidity Pools

GET /liquidity_pools?reserves={:reserves}&cursor={paging_token}&order={asc,desc}&limit={1-200}
```

```js
Endpoints

GET /liquidity_pools
GET /liquidity_pools/:liquidity_pool_id
GET /liquidity_pools/:liquidity_pool_id/effects
GET /liquidity_pools/:liquidity_pool_id/transactions
GET /liquidity_pools/:liquidity_pool_id/operations
```

```js
Liquidity Pool Deposit

Parameters         Type                      Description

Liquidity Pool ID  liquidityPoolID           The PoolID for the Liquidity Pool to deposit into
Max Amount A       integer                   Maximum amount of first asset to deposit
Max Amount B       integer                   Maximum amount of second asset to deposit
Min Price	       {numerator, denominator}  Minimum depositA/depositB
Max Price          {numerator, denominator}  Maximum depositA/depositB
```

```js
Liquidity Pool Withdraw

Parameters         Type                      Description

Liquidity Pool ID  liquidityPoolID           The PoolID for the Liquidity Pool to withdraw from
Amount             integer                   Amount of pool shares to withdraw
Min Amount A       integer                   Minimum amount of the first asset to withdraw
Min Amount B       integer                   Minimum amount of the second asset to withdraw
```

![GitHub Logo](/images/repo.svg)

[Developer discussion about possible changes to the protocol](https://github.com/stellar/stellar-protocol)


### Protocol 18

Stellar Protocol 18 enables the creation of Automated Market Makers (AMMs).

[Stellar Public Network Protocol 18 Upgrade Vote](https://status.stellar.org/incidents/d8d1phjglcr3) on Wed Nov 03 2021 at 17:00:00 GMT+0200 (Eastern European Standard Time).

At this time, validators will vote on whether to upgrade to Stellar protocol 18.

If the vote goes through, the network upgrade is immediate.

To prepare, install up-to-date versions of any Stellar-related software you use.

For more info, see Stellar.Org [Upgrade Guide](https://stellar.org/developers-blog/protocol-18-upgrade-guide)

### xlmLIQUIDITY

xlmLIQUIDITY is a liquidity provider on Stellar blockchain.

Add xlmLIQUIDITY trustline

#### Code
xlmLIQUIDITY

#### Issuer
GBEAPUJKWP32U4HXGTSKJ4NPVBYY5JEKUBFWHSL7OUZGF4EZWACVM7W4

#### Domain
xlmliquidity.io

#### QR Code

![Add Trustline](/images/trustline.png)