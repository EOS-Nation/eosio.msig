# EOSIO MSIG

## Resources

- `v1.8.3-inline-msig` release candidate: https://github.com/EOSIO/eosio.contracts/releases/tag/v1.8.3-inline-msig


## EOSIO CDT compiler

```
$ eosio-cpp --version
eosio-cpp version 1.6.3
```

## Build

```
git clone git@github.com:EOSIO/eosio.contracts.git
cd eosio.contracts
git checkout v1.8.3-inline-msig
./build.sh
```

## Checksum

Branch `v1.8.3-inline-msig` (last commit `c097d54`)

https://github.com/EOSIO/eosio.contracts/tree/v1.8.3-inline-msig

```bash
$ shasum -a 256 eosio.msig.wasm

9ff835502748819aee18db04028eb26f7089293f4b8b3692cfc39ef6622cd2f5  eosio.msig.wasm
```

## Deployed on Jungle 3 testnet

```
$ cleos -u http://jungle.eosn.io get code eosio.msig
code hash: 9ff835502748819aee18db04028eb26f7089293f4b8b3692cfc39ef6622cd2f5
```