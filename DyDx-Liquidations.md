# DyDx Liquidations 
DyDx Liquidations succeed because backrunners are quick to exploit the MEV. 

To put simply, transaction A is broadcasted with a slightly lower gas price than already pending transaction B so that A gets mined right after B in the same block.
(eg. to execute a DyDx liquidation after a price oracle update that triggers a DyDx loan to go under the required collateralization ratio).

Fairly interesting! To learn more about it: 

## Articles
- [Liquidators: The Secret Whales Helping DeFi Function](https://medium.com/dragonfly-research/liquidators-the-secret-whales-helping-defi-function-acf132fbea5e)
-m[Quantifying Blockchain Extractable Value: How dark is the forest?](https://arxiv.org/pdf/2101.05511.pdf)
-m[Random ordering of equally-priced transactions incentivises competitive spam](https://github.com/ethereum/go-ethereum/issues/21350)
- [Flashbots: Frontrunning the MEV Crisis](https://medium.com/flashbots/frontrunning-the-mev-crisis-40629a613752)

## Technical
- [Official DyDx Liquidator Bot](https://github.com/dydxprotocol/liquidator)
- [Etherscan Addresses of DyDx Liquidations](https://gist.github.com/hendrikhofstadt/6165e6a1a9baf07453cb96edfc8e5ef6)
- [How to build a liquidator bot for DeFi](https://powpark.com/post/2020-06-19-how-to-build-a-liquidator-bot-defi/)
