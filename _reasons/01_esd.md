---
permalink: /esd/
title: What is Empty Døllar Set?
intro: An algorithmic stablecoin to power the future of finance.
---

Empty Døllar Set — or ESD — is a cryptocurrency whose value is designed to track the US Dollar. Unlike stablecoins that are backed by physical dollars or collateral, such as USDC and DAI, the value of ESD is designed to be maintained through *market forces*.

Here’s how it works, in a nutshell:

1. *Contraction* — When the market price of ESD is less than $1, the protocol stops emissions, and begins offering “coupons” (debt) for sale at a premium, meaning you can buy a 1 ESD “IOU” for something less than 1 ESD. You pay for coupons by “burning” ESD. The burning of ESD reduces the total supply, which should drive the price *higher*.

2. *Expansion* — When the market price of ESD is greater than $1, the protocol emits new ESD coins. This increase in supply should drive the price *lower*. The newly emitted coins are used first to buy back any debt (coupons), and then are awarded to people who lock up ESD in the “DAO”, and people who provide trading liquidity on Uniswap.

These two see-saw mechanisms are designed to work in tandem to keep the price of ESD oscillating around one US Dollar.

Useful terminology:

*Bonding* — Earning rewards in the ESD app requires staking or locking-up tokens. In ESD, staking is referred to as “bonding”.

*Epochs* — In order to attenuate changes in liquidity in the DAO and on Uniswap, the ESD protocol includes some built-in withdrawal delays, which are calculated in units of “epochs”. One epoch is eight hours.

*TWAP* — In order to dampen volatility, changes in expansion and contraction are not triggered by the current market price of ESD, but rather the “TWAP”, or time-weighted average price.

At the time of this writing, ESD is getting a lot of press because of the high APRs paid to DAO stakers, liquidity providers, and coupon purchasers.

Let’s explore those three ways to earn ESD, [beginning with the DAO.](/dao/) →