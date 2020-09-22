# EOSIO MSIG

## Resources

- `v1.8.3-inline-msig-patch2` release candidate: https://github.com/EOSIO/eosio.contracts/releases/tag/v1.8.3-inline-msig-patch2


## EOSIO CDT compiler

```
$ eosio-cpp --version
eosio-cpp version 1.6.3
```

## Build

```
git clone git@github.com:EOSIO/eosio.contracts.git
cd eosio.contracts
git checkout v1.8.3-inline-msig-patch2
./build.sh
```

## Checksum

Branch `v1.8.3-inline-msig-patch2` (last commit `0ebd5f3`)

https://github.com/EOSIO/eosio.contracts/tree/v1.8.3-inline-msig-patch2

```bash
$ shasum -a 256 eosio.msig.wasm

055f1cd3bffc3262ccd40a0acd665a0a62e4a7cc48f34f6fc54aa74928cbac13  eosio.msig.wasm
```

## Deployed on Jungle 3 testnet

```
$ cleos -u http://jungle.eosn.io get code eosio.msig
code hash: 055f1cd3bffc3262ccd40a0acd665a0a62e4a7cc48f34f6fc54aa74928cbac13
```