## Fund Me

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Help command lines


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

#use make
$ make help
```

