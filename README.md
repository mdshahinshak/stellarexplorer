{ "_links": { "self": { "href": "https://api.mainnet.minepi.com/transactions/20ced347b6aade9c7a71c16bf3538ecb69e0e93ff3f69b292ef171f1d28cf158" }, "account": { "href": "https://api.mainnet.minepi.com/accounts/GAMKYTNROV3C4TMC6U7UQCLXHSLFKS6TI556S3FMR32YMCX5XVABK2A2" }, "ledger": { "href": "https://api.mainnet.minepi.com/ledgers/15138594" }, "operations": { "href": "https://api.mainnet.minepi.com/transactions/20ced347b6aade9c7a71c16bf3538ecb69e0e93ff3f69b292ef171f1d28cf158/operations{?cursor,limit,order}", "templated": true }, "effects": { "href": "https://api.mainnet.minepi.com/transactions/20ced347b6aade9c7a71c16bf3538ecb69e0e93ff3f69b292ef171f1d28cf158/effects{?cursor,limit,order}", "templated": true }, "precedes": { "href": "https://api.mainnet.minepi.com/transactions?order=asc&cursor=65019766137430016" }, "succeeds": { "href": "https://api.mainnet.minepi.com/transactions?order=desc&cursor=65019766137430016" }, "transaction": { "href": "https://api.mainnet.minepi.com/transactions/20ced347b6aade9c7a71c16bf3538ecb69e0e93ff3f69b292ef171f1d28cf158" } }, "id": "20ced347b6aade9c7a71c16bf3538ecb69e0e93ff3f69b292ef171f1d28cf158", "paging_token": "65019766137430016", "successful": true, "hash": "20ced347b6aade9c7a71c16bf3538ecb69e0e93ff3f69b292ef171f1d28cf158", "ledger": 15138594, "created_at": "2024-06-10T16:42:08Z", "source_account": "GCDRRMY3LR3EYCIFNV5TN7RSS4VHGGQF4TW4QSONSA75W4K3UCZMKOSV", "source_account_sequence": "60648687725969410", "fee_account": "GCDRRMY3LR3EYCIFNV5TN7RSS4VHGGQF4TW4QSONSA75W4K3UCZMKOSV", "fee_charged": "100000", "max_fee": "100000", "operation_count": 1, "envelope_xdr": "AAAAAgAAAAAYrE2xdXYuTYL1P0gJdzyWVUvTR3vpbKyO9YYK/b1AFQABhqAA13epAAAAAgAAAAEAAAAAAAAAAAAAAABmZy2SAAAAAAAAAAEAAAAAAAAAAQAAAACHGLMbXHZMCQVtezb+MpcqcxoF5O3ISc2QP9txW6CyxQAAAAAAAAAAGVT8QAAAAAAAAAAB/b1AFQAAAECOkwlCuI85InnjWeMMdgoFkA1Hnc5iyhla2fqlkBvx2y1zENyS3Sxa10sQHfrpGb/pASwbdT2hrab3+v+KyFcI", "result_xdr": "AAAAAAABhqAAAAAAAAAAAQAAAAAAAAABAAAAAAAAAAA=", "result_meta_xdr": "AAAAAgAAAAIAAAADAOb/IgAAAAAAAAAAGKxNsXV2Lk2C9T9ICXc8llVL00d76WysjvWGCv29QBUAAAAAGe3zZADXd6kAAAABAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAAAAABAOb/IgAAAAAAAAAAGKxNsXV2Lk2C9T9ICXc8llVL00d76WysjvWGCv29QBUAAAAAGe3zZADXd6kAAAACAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAAAAABAAAABAAAAAMA5v8iAAAAAAAAAAAYrE2xdXYuTYL1P0gJdzyWVUvTR3vpbKyO9YYK/b1AFQAAAAAZ7fNkANd3qQAAAAIAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAEA5v8iAAAAAAAAAAAYrE2xdXYuTYL1P0gJdzyWVUvTR3vpbKyO9YYK/b1AFQAAAAAAmPckANd3qQAAAAIAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAMA5v6yAAAAAAAAAACHGLMbXHZMCQVtezb+MpcqcxoF5O3ISc2QP9txW6CyxQAAAAAA3dwtAMGrpwAAAXkAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAEA5v8iAAAAAAAAAACHGLMbXHZMCQVtezb+MpcqcxoF5O3ISc2QP9txW6CyxQAAAAAaMthtAMGrpwAAAXkAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAA=", "fee_meta_xdr": "AAAAAgAAAAMA4ZqLAAAAAAAAAAAYrE2xdXYuTYL1P0gJdzyWVUvTR3vpbKyO9YYK/b1AFQAAAAAZ73oEANd3qQAAAAEAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAEA5v8iAAAAAAAAAAAYrE2xdXYuTYL1P0gJdzyWVUvTR3vpbKyO9YYK/b1AFQAAAAAZ7fNkANd3qQAAAAEAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAA==", "memo_type": "none", "signatures": [ "jpMJQriPOSJ541njDHYKBZANR53OYsoZWtn6pZAb8dstcxDckt0sWtdLEB366Rm/6QEsG3U9oa2m9/r/ishXCA==" ], "valid_after": "1970-01-01T00:00:00Z", "valid_before": "2024-06-15T16:45:06Z"

[![Build Status](https://travis-ci.org/chatch/stellarexplorer.svg?branch=master)](https://travis-ci.org/chatch/stellarexplorer)

A ledger explorer for [Stellar](https://stellar.org).

Public: https://steexp.com
Test: https://testnet.steexp.com
Local: http://localhost:3000

## Resources

### Lists

| Resource     | URI                                          |
| ------------ | -------------------------------------------- |
| Operations   | [/operations](https://steexp.com/operations) |
| Transactions | [/txs](https://steexp.com/txs)               |
| Ledgers      | [/ledgers](https://steexp.com/ledgers)       |
| Payments     | [/payments](https://steexp.com/payments)     |
| Trades       | [/trades](https://steexp.com/trades)         |
| Effects      | [/effects](https://steexp.com/effects)       |

### Directory

| Resource  | URI                                        |
| --------- | ------------------------------------------ |
| Assets    | [/assets](https://steexp.com/assets)       |
| Anchors   | [/anchors](https://steexp.com/anchors)     |
| Exchanges | [/exchanges](https://steexp.com/exchanges) |

### Accounts

| Resource             | URI                                                                                                                                                      |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| by Federated address | [/account/stellar\*fed.network](https://steexp.com/account/stellar*fed.network)                                                                          |
| by Public address    | [/account/GAREELUB43IRHWEASCFBLKHURCGMHE5IF6XSE7EXDLACYHGRHM43RFOX](https://steexp.com/account/GAREELUB43IRHWEASCFBLKHURCGMHE5IF6XSE7EXDLACYHGRHM43RFOX) |

#### Tabs

| Resource         | URI                                                                                                       |
| ---------------- | --------------------------------------------------------------------------------------------------------- |
| Balances Tab     | [/account/stellar\*fed.network#balances](https://steexp.com/account/stellar*fed.network#balances)         |
| Payments Tab     | [/account/stellar\*fed.network#payments](https://steexp.com/account/stellar*fed.network#payments)         |
| Offers Tab       | [/account/stellar\*fed.network#offers](https://steexp.com/account/stellar*fed.network#offers)             |
| Trades Tab       | [/account/stellar\*fed.network#trades](https://steexp.com/account/stellar*fed.network#trades)             |
| Effects Tab      | [/account/stellar\*fed.network#effects](https://steexp.com/account/stellar*fed.network#effects)           |
| Operations Tab   | [/account/stellar\*fed.network#operations](https://steexp.com/account/stellar*fed.network#operations)     |
| Transactions Tab | [/account/stellar\*fed.network#transactions](https://steexp.com/account/stellar*fed.network#transactions) |
| Signing Tab      | [/account/stellar\*fed.network#signing](https://steexp.com/account/stellar*fed.network#signing)           |
| Flags Tab        | [/account/stellar\*fed.network#flags](https://steexp.com/account/stellar*fed.network#flags)               |
| Data Tab         | [/account/stellar\*fed.network#data](https://steexpcom/account/stellar*fed.network#data)                  |

### Search

| Resource              | URI                                                                                                                                                                    |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Federated address     | [/search/steexp\*fed.network](https://steexp.com/search/steexp*fed.network)                                                                                            |
| Public address        | [/search/GAREELUB43IRHWEASCFBLKHURCGMHE5IF6XSE7EXDLACYHGRHM43RFOX](https://steexp.com/search/GAREELUB43IRHWEASCFBLKHURCGMHE5IF6XSE7EXDLACYHGRHM43RFOX)                 |
| Ledger                | [/search/10000000](https://steexp.com/search/10000000)                                                                                                                 |
| Transaction           | [/search/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071](https://steexp.com/search/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071) |
| Asset Code            | [/search/NGN](https://steexp.com/search/NGN)                                                                                                                           |
| Anchor Name           | [/search/ripplefox](https://steexp.com/search/ripplefox)                                                                                                               |
| Anchor Name (Partial) | [/search/fox](https://steexp.com/search/fox)                                                                                                                           |

### Misc

| Resource    | URI                                                                                                                                                            |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Transaction | [/tx/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071](https://steexp.com/tx/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071) |
| Ledger      | [/ledger/10000000](https://steexp.com/ledger/10000000)                                                                                                         |
| Anchor      | [/anchor/apay.io](https://steexp.com/anchor/apay.io)                                                                                                           |
| Asset       | [/asset/NGN](https://steexp.com/asset/NGN)                                                                                                                     |

## Exploring Private / Local Development Networks<a name="private-networks"></a>

steexp will connect to a local horizon instance at http://localhost:8000 by default. If your running a local private network for development this is quite handy for browsing your changes to the ledger.

Alternatively you can run locally connecting to the testnet or public network horizon instances. To do this define these aliases to localhost:

```
127.0.1.1  testnet.local     # for steexp use testnet horizon
127.0.1.1  publicnet.local   # for steexp use mainnet horizon
```

Navigate to http://testnet.local:3000 or http://publicnet.local:3000 to select the network your interesting in exploring.

## Development

See the section [Exploring Private / Local Development Networks](#private-networks) for connecting to different backend networks. By default steexp will look for a local instance of horizon.

Start:

```
npm i && npm start
```

Test:

```
npm i && npm test
```

Build:

```
npm i && npm run build
```

## Languages

Use the language selector in the top right corner to change the language.

Translation files are here:
https://github.com/chatch/stellarexplorer/tree/master/src/languages

Submit pull requests with new languages or languages fixes there.
