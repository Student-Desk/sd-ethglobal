**Coinbase Wallet:** Integrated Coinbase connects non custodial wallet for users.

## Coinbase Wallet Implementation: 

```
 walletlink: {
    package: CoinbaseWalletSDK, // Required
    options: {
      appName: "GigConomy", // Required
      infuraId: process.env.REACT_APP_INFURA_KEY, // Required unless you provide a JSON RPC url; see `rpc` below
    },
  },

```
