# arc-sub-lite

Simple subscription registry on Arc testnet.

- Chain ID: `5042002`
- RPC: `https://rpc.testnet.arc.network`
- USDC: `0x3600000000000000000000000000000000000000`
- Explorer: https://testnet.arcscan.app

## Contract

`src/SubLite.sol` records USDC payments and emits accounting events.

## Build

```bash
forge build
```

## Deployment

- Contract: `0xb9bf780987007E01BCF81Dce5a062841d1f9E4a8`
- Tx: `inferred-from-nonce`
- Explorer: https://testnet.arcscan.app/address/0xb9bf780987007E01BCF81Dce5a062841d1f9E4a8
