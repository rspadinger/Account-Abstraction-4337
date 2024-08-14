# Account Abstraction Resources

-   [Vitalik Buterin](https://ethereum-magicians.org/t/implementing-account-abstraction-as-part-of-eth1-x/4020)
-   [EntryPoint Contract v0.6](https://etherscan.io/address/0x5ff137d4b0fdcd49dca30c7cf57e578a026d2789)
-   [EntryPoint Contract v0.7](https://etherscan.io/address/0x0000000071727De22E5E9d8BAf0edAc6f37da032)
-   [zkSync AA Transaction Flow](https://docs.zksync.io/build/developer-reference/account-abstraction.html#the-transaction-flow)

## Requirements

-   [foundry](https://getfoundry.sh/)
-   [foundry-zksync](https://github.com/matter-labs/foundry-zksync)
-   [JQ](https://jqlang.github.io/jq/)

# Quickstart

```bash
foundryup
make test
```

### User operation - Arbitrum

```bash
make sendUserOp
```

## zkSync Foundry

```bash
foundryup-zksync
make zkbuild
make zktest
```
