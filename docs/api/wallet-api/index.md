<!-- Code generated by github.com/filecoin-shipyard/js-lotus-client/docgen. DO NOT EDIT. -->
# Wallet API

Enable the API by passing the `walletApi` schema to `LotusRPC` e.g.

```js
import { LotusRPC } from '@filecoin-shipyard/lotus-client-rpc'
import { mainnet } from '@filecoin-shipyard/lotus-client-schema'
import { NodejsProvider } from '@filecoin-shipyard/lotus-client-provider-nodejs'

const provider = new NodejsProvider('<PROVIDER_URL>')
const client = new LotusRPC(provider, { schema: mainnet.walletApi })
``` 

<small>Lotus source: [github.com/filecoin-project/lotus/api/api_wallet.go](https://github.com/filecoin-project/lotus/blob/master/api/api_wallet.go)</small>


## API Reference

* [Wallet](wallet.md)
    * [walletDelete](wallet.md#walletdelete)
    * [walletExport](wallet.md#walletexport)
    * [walletHas](wallet.md#wallethas)
    * [walletImport](wallet.md#walletimport)
    * [walletList](wallet.md#walletlist)
    * [walletNew](wallet.md#walletnew)
    * [walletSign](wallet.md#walletsign)
