---
title: CoinTracker opportunities
tags: cointracker
description: CoinTracker opportunities open info (OI)
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

<h1 style="text-align: center;">CoinTracker opportunities</h1>

#### Prioritization key
- P0: Important and time-sensitive blocker in moving forward
- P1: Important and and not as time-sensitive
- P2: Nice to have currently
- P3: Nice to have in the future

# Open

## Tools

### Lock past tax years (P0 | In-progress 2024-01-09)

#### About
- Lock the specified past tax year's transactions (txns) from being updated when the connected sources pull in new txn data
- This is important to avoid previously fixed issues from being unintentionally changed

#### Resources
- [Allow the option to "freeze" or lock transactions by tax year.](https://cointracker.canny.io/features/p/allow-the-option-to-freeze-or-lock-transactions-by-tax-year) *on CoinTracker Feature Requests*
- [r/Cointracker post](https://www.reddit.com/r/Cointracker/comments/192ot15/does_cointracker_plan_to_build_this_for_2024/)

### Filters
See [filters](https://hackmd.io/@openinfo/cointracker/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fcointracker-about#Opportunities)

### Import and export across providers (P2)
- Importing/exporting accurate data across most software providers is not easy to do
- Import and export tax lot data

## Integrations

### Networks (P1)
- Gnosis Chain DAI
    - High usage for payments
- Arweave AR
    - High usage with developers for app storage

### Centralized exchanges CEXs (P1)
- Ledn API
    - The only centralized exchange lending provider in North America to survive the liquidation events of 2022

### Chainlink staking (P2)
Track Chainlink (LINK) staking deposits, withdrawals, and rewards

### Lending tokens (P2)
Auto track earned interest income while holding tokens (e.g. AAVE)

## Onboarding

### Bulk add addresses (P2)
- Add a list of account addresses
- Adding dozens of addresses across multiple networks can take hours
- Potential solutions
    - Copy and paste UX view
    - CSV upload

## Other

### Audit protection plan (P2)
[TurboTax audit protection plan open info (OI)](https://hackmd.io/@openinfo/turbotax/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fturbotax-about#TurboTax-audit-protection)

# Resolved

## Integrations

### Coinbase duplicate transactions (P0)
- Marked as resolved _2021-11-01_
- Transfers from Coinbase wallets: ETH transfers creates 2 separate txns.
  1. Coinbase outflow combining the transfer amount + fee in the amount while showing $0 fee
  2. Wallet inflow with correct amount + fee. This requires creating 1 new manual entry to reflect the amount and fee and ignoring the 2 auto generated events.
- *See [Roadmap > Bugs > Coinbase duplicate transactions](https://feedback.cointracker.io/bugs/p/coinbase-duplicate-transactions)*

### Liquidity pools (LPs) (P2)
- *See [Liquidity transactions on CoinTracker](https://support.cointracker.io/hc/en-us/articles/20897601327505-Liquidity-transactions-on-CoinTracker)*
- Option to transfer the cost basis when depositing into and withdrawing from liquidity pools
- Access setting: Select your profile username (Top-right menubar) > "Settings" > "Tax" tab > "Treat liquidity pool transactions as non-taxable"

<p style="text-align: center; font-style: italic">This is not financial, technical, or legal advice. Do your own research and consult professionals.</p>