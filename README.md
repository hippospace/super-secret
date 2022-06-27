# super-secret

At Hippo we're super into devtools for the Move language. If any of these ideas tickle you, send us a note!

- (not secret anymore) we're working on a Move -> TypeScript transpiler that can:
  - automate TypeScript SDK generation
  - emulate Move contract execution in JavaScript
  - provide single-stepping debugging capabilities (in emulation environment)
- A decoration language + transpiler that automatically turns Move modules into Indexer queries to gather protocol metrics (e.g. tvl, volume, daily inflow/outflow)
- A decoration language + transpiler that automatically turns Move modules into web and mobile UI, so as to allow developers to experiment with new protocol designs rapidly, share and gather feedback from community members, without the need to build a polished UI
- A unified language that generates all the components of a web3 application, end-to-end, including:
  - smart contract (in Move/Solidity)
  - UI
  - SDK (connects UI to chain & off-chain data sources)
  - bots (perform service maintenance, e.g. liquidation & arb bots)

Some of the DeFi-focused ideas that we're happy to discuss in a super secret github issue or something:

- A concentrated liquidity pool connected to an oracle so as to eliminate the need for active LP management
- A lending protocol that supports arbitrary token to be used as collateral, and computes the LTV & deposit cap of each collateral dynamically by evaluating the amount of liquidity available from a set of compatible AMMs that are used for liquidation.
- An on-chain exchange that aggregates liquidity from multiple CEX.
  - That takes multiple blocks to settle
  - That settles in the same block (no capital lockup)


For all the ideas above, we actually know how to implement them. But there is no way we can do all of them on our own! If you want to learn more, find `mana | hippo` from Aptos' discord `dev-discussion` channel.
