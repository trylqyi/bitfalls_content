# MakerDAO and the Dai Stability Engine

MakerDAO is a smart contracts platform harnessing the design rationale and underlying logic of the Ethereum protocol to leverage a market stability and currency management engine in response to the perpetual volatility swings plaguing the realm of crypto economic markets and quasi-institutional blockchain alignments.

The Maker platform brings whole new dimensions to the landscape of possibilities and ways of thinking about the above's relationships to traditional markets, capital flows broadly, diagnostic correlations and general risk assessment in complexly entangled scenarios.

An integral component of the Maker platform is its governance token, MKR, which entitles its holders to vote on critical changes and adjustment of system parameters. As such, Maker has nurtured a particular, well-informed and competent culture of contributors organized around common interest and motivations, and lively ongoing theoretic speculations in their public chat.

In that sense, MakerDAO's undertaking to assemble and iron out a machinery of algorithmic-contractual mechanisms and financial instruments that propel towards producing organically stable assets and re-route exposure to blockchain external market flows (e.g., tokenized Proof-of-Asset gold certificates, as [announced in partnerships with DigixDAO](https://medium.com/@Digix/partnership-announcement-makerdao-and-digix-dgx-gold-tokens-to-play-a-crucial-role-in-the-dai-8ed4c05b622c), a similarly oriented and complementary Ethereum platform working to leverage its Digix Gold Tokens as collateral on Maker) in probing for ways to rationalize and legitimize crypto asset finance makes it a unique paradigm in itself.

How Maker accomplishes this is through a set of Collateralized Debt Positions (CDPs), Autonomous Feedback Mechanisms and appropriately incentivized actors structured around a system of smart contracts (token wrappers, market makers, etc.) and specialized integrated Decentralized Exchanges.

Dai, the stablecoin (an ERC-20 token) which Maker currently targets to a soft peg 1:1 to the US dollar is the initial result. Dai is produced by locking CDPs in smart contracts, with Pooled Ether (PWETH) being the single currently supported collateral, but with the foresight and end goal of accumulating high-quality diversified collateral portfolio.

In brief example, if a person who needs to cash out some of his ETH, but believes the price will grow, he could lock some amount of ETH in a CDP and receive a certain amount of guaranteed 1:1 USD. The maximum amount of Dai in proportion to the ETH locked is specified in the parameters of the CDP itself, while the liquidation ratio (the price under which ETH shouldn't plunge before the withdrawn amount of Dai are paid back to unlock the CDP) is adjusted by the borrower.

This also introduces a margin trading leverage mechanism as one could buy more ETH for the Dai borrowed, but the math should be adequately intuited in reasonable upper/lower bounds of, preferably, worst case scenario expectations (a Bayesian approach is useful to adopt).

In the event of severe market instability, a certain threshold triggers the automatic feedback mechanisms which dilute MKR tokens by creating and selling them on the open market until the price of Dai (which temporarily breaks the soft peg, but maintains the denomination) re-calibrates against supply/demand forces. These osmotic relationships are a central aspect of the system, and how are the unique parameters of each CDP adjusted.

The Dai stablecoin itself had initially been thought of being soft-pegged to IMF's SDR currency basket, so even the present choice of USD denomination is to be temporary and eventually replaced by something that guarantees stability independent of the outlook of the US economy. A custom, dynamic low-volatility currency basket is conceived to eventually be introduced.




