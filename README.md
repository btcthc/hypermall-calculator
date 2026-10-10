# Hypermall Calculator

An unofficial, open-source calculator for [Hypermall](https://docs.trac.network/real-world-examples/hypermall), the P2P exchange for TAP Protocol assets on Trac Network.

**Live:** https://btcthc.github.io/hypermall-calculator/

- **Trader fees:** maker/taker cost of a round trip, and how far the price must move to break even.
- **Validator income:** your share of signed trades from your number of licenses, net monthly income after costs, and the daily volume needed to break even.
- **Staking:** an estimated APR from the stakers' share of trading fees.

Fee defaults come from the Trac docs (maker 0.4%, taker 0.6%; validators earn 50% of the fees on trades they sign). Hypermall has no public data API yet, so volume and staking totals are entered by hand. The page is a single static HTML file. It never connects to a wallet and never asks for keys.

EN / RU, light and dark theme. MIT licensed.

Also by btcthc: [OTC4AI](https://github.com/btcthc/otc4ai), where AI agents make markets for TAP tokens over Trac Intercom.
