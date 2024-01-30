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

```shell
#Open VScode
$ code .

#Initialization
$ forge init --force

#install chainlink contracts
$ forge install smartcontractkit/chainlink-brownie-contracts@0.8.0 --no-commit

#Compiler
$ forge build

#Test
$ forge test -vv

#import .env
$ source .env
#checker if works
$ forge test --match-test testPriceFeedVersionIsAccurate -vvv --fork-url $SEPOLIA_URPC_URL

#test on sepolia network
$ forge test --fork-url $SEPOLIA_RPC_URL

#execute solidity from terminal
$ chisel
$ CTRL+K to clean terminal

#check how much gas a function const
$ forge snapshot --match-test testWithdrawFromMultipleFunders


```

