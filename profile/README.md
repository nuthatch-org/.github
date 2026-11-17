## nuthatch: be your own indexer

**[nuthatch](https://github.com/nuthatch-org/nuthatch)** turns an EVM contract's history into a local SQL database. One Rust binary, no Postgres, no subgraph to write, and an MCP server built in, so a coding agent can query what it indexed.

```sh
curl -fsSL https://nuthatch-indexer.com/install.sh | sh
nuthatch init 0xA0b86991c6218b36c1D19D4a2e9Eb0cE3606eB48 --alias usdc --chain mainnet
nuthatch dev --backfill 300
```

**Also here**

- [burrmill](https://github.com/nuthatch-org/burrmill): the SQL engine inside nuthatch, on DataFusion, with exact integer arithmetic that refuses to return a wrapped sum
- [nests](https://github.com/nuthatch-org/nests): prebuilt nests (Uniswap, Aave, ENS, Lido and more) you can run on your own machine
- Nests for real projects: [polymarket-nest](https://github.com/nuthatch-org/polymarket-nest), [aztec-staking-nest](https://github.com/nuthatch-org/aztec-staking-nest), [pwnpot-nest](https://github.com/nuthatch-org/pwnpot-nest), [din-nest](https://github.com/nuthatch-org/din-nest)

Docs and blog: [nuthatch-indexer.com](https://nuthatch-indexer.com). Questions: [Discord](https://discord.gg/p9Xc45txWa).
