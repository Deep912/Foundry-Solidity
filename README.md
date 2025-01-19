## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose Solidity REPL.

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

---

## My Solidity Adventure 🚀

Welcome to my **Solidity + Foundry framework learning journey**—or as I like to call it, the "road to blockchain wizardry." 🧙‍♂️✨ This repo is where I boldly experiment, break things (on purpose... mostly), and occasionally wonder why gas fees aren’t paid in actual fuel. ⛽

Think of it as my blockchain diary—filled with triumphs, bugs, and enough `require` statements to make my head spin. Follow along as I try to forge (pun intended) my way into the world of smart contracts!

Expect to see:
- **Code that works** (eventually, after enough tears).
- **Gas wars with myself** (because apparently, I like pain).
- **Deployments that might break the blockchain (but hey, that’s someone else’s problem, right?).**

### Why am I doing this? 🧐

Great question. Is it because I love the thrill of debugging code at 2 AM? Or maybe I just enjoy yelling "it works on my machine!" before realizing I forgot to set the gas limit. Either way, this journey is part coding, part chaos, and 100% entertainment (for you, not always for me).

If you're learning Solidity too, grab some popcorn 🍿, and watch me try not to `revert` my progress. Pro tip: bring a debugger and a sense of humor—you’ll need both!
