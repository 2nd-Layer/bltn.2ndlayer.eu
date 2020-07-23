# [bltn.2ndlayer.eu](https://bltn.2ndlayer.eu)
Better Late Than Never | Cardano Stake Pool

[GitHub Pages hosted version](https://2nd-layer.github.io/bltn.2ndlayer.eu/)

## Cardano Shelley ITNv1 Overview
Current Cardano Shelley Incentivized Testnet v1 is operated using Rust codebase with a 
[Jormungandr node](https://github.com/input-output-hk/jormungandr).
Jormungandr uses [Poldercast p2p pub/sub](https://github.com/primetype/poldercast) for transaction (fragments) and block distribution
between individual nodes of the topology.

Here we track those we deem significant issues or required enhancements for poldercast to be the effective pub/sub for future Cardano mainnet, Shelley v2 let's say. Which [mentioned CH in this AMA 03-Jan-2020](https://www.youtube.com/watch?v=CBGYIHb600w&feature=youtu.be&t=2272).

### [Poldercast issues](https://github.com/primetype/poldercast/issues)
- [ ] [Rust Poldercast](https://github.com/primetype/poldercast) does not support [static topology, issue #21](https://github.com/primetype/poldercast/issues/21)

### [Jormungandr issues](https://github.com/input-output-hk/jormungandr/issues/)
- [ ] Node Peer overview and control in Jormungandr, issue [#883](https://github.com/input-output-hk/jormungandr/issues/883)
