# RecurX Ecosystem

Welcome to the **RecurX** smart contract repository. This repository contains the core contracts for the RecurX ecosystem, including the RCX Token, the PublicSale Launchpad, and the Vesting Factory.

## Mainnet Deployments (BSC)

All contracts are fully verified and deployed on the Binance Smart Chain (BSC) Mainnet. 

### 1. RCX Token
The native ERC20 token for the RecurX ecosystem.
- **Proxy Address (Interact Here):** [0x7c533FF74f965e9E040EDBc6b4322601eB9Fe022](https://bscscan.com/address/0x7c533FF74f965e9E040EDBc6b4322601eB9Fe022#readProxyContract)
- **Implementation (View Code Here):** [0x092b79a652eb82e3b8e2aaf9c308ff8cd4108be8](https://bscscan.com/address/0x092b79a652eb82e3b8e2aaf9c308ff8cd4108be8#code)

### 2. PublicSale Launchpad
The launchpad contract handling the public token sale across multiple pricing stages.
- **Proxy Address (Interact Here):** [0x25bb13b3bf10e5518a82896d0e7ef889806e6cc8](https://bscscan.com/address/0x25bb13b3bf10e5518a82896d0e7ef889806e6cc8#readProxyContract)
- **Implementation (View Code Here):** [0xc6e11aecabf1a7f7c8929df07c848ef8f252e8c5](https://bscscan.com/address/0xc6e11aecabf1a7f7c8929df07c848ef8f252e8c5#code)

### 3. RCXVestingFactory
The factory contract responsible for managing token vesting allocations.
- **Contract Address (View Code & Interact):** [0xb38e9fa666797dec88e861b46d31bc677d26eaaa](https://bscscan.com/address/0xb38e9fa666797dec88e861b46d31bc677d26eaaa#code)

> **Note on Proxies:** The RCX Token and PublicSale contracts utilize an Upgradeable `ERC1967Proxy` architecture. If you wish to read the raw Solidity code (`.sol` files), click the **Implementation** links. If you wish to read balances or write transactions, use the **Proxy** links.

---

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
