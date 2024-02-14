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

### Data management

#### Lock past tax years (P0 | In-progress 2024-01-09)

##### About
- Lock the specified past tax year's transactions (txns) from being updated when the connected sources pull in new txn data
- This is important to avoid previously fixed issues from being unintentionally changed

##### Resources
- [Allow the option to "freeze" or lock transactions by tax year.](https://cointracker.canny.io/features/p/allow-the-option-to-freeze-or-lock-transactions-by-tax-year) *on CoinTracker Feature Requests*
- [r/Cointracker post](https://www.reddit.com/r/Cointracker/comments/192ot15/does_cointracker_plan_to_build_this_for_2024/)

#### Universal import and export data across providers (P2)
- Importing/exporting accurate data across most software providers is not easy to do
- Import and export tax lot data in a widely accepted format

### Edit transactions (Txns)

#### Link missing outflow/inflow transactions (P1)
- Link a missing outflow/inflow transaction (txn) to it's matching inflow/outflow txn when both txns exist in CoinTracker and are not showing as "connected"
    - The txns not being "connected" results in an correct gain/loss
    - Less steps for the user to select both txns and link compared to using a workaround
    - Less risk of errors since it doesn't require ignoring correct txns
- Workaround
    - Edit the outflow/inflow txn to add the matching side of the txn with the source account
    - Ignore the original (now duplicated) txn

#### Edit transaction view timestamps (P1)
- Expect: Edit the timestamps for transactions (txns) sourced from networks and APIs directly
- Observe: Only txn timestamps sourced from CSV uploads and manual additions can be edited
- About: Accounts, wallets, and exchanges often have different definitions of txn network finalization
    - Timestamps can be different for the same transfer txn
    - This creates missing inflow/outflow issues
- Workaround: Manually add a new txn resolving the timestamp discrepancy betweens sources and ignore the txn(s) from the network/API.

### Filters
See [filters](https://hackmd.io/@openinfo/cointracker/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fcointracker-about#Opportunities)

## Integrations

### CSV uploads
See [CSV uploads](https://hackmd.io/@openinfo/cointracker/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fcointracker-about#Opportunities1)

### Smart contract accounts

#### Safe (P1)
- Features
    - Autodetect outflow/inflow transactions from Safe accounts as transfers and fees paid from Safe approval accounts, i.e. Accounts that are part of the multisig
    - Edit transaction fees
        - Add fee amount with a different account source, i.e. Safe approval account traditionally pays the network fee
        - Safe accounts will pay the network fee directly with future Ethereum improvement proposals (EIPs)
- About
    - $80b of assets stored in Safes: [@SchorLukas X post 2024-01-13](https://twitter.com/SchorLukas/status/1746154634442400228)
    - Many startups use Safe for asset storage and onchain team permissions
    - Many new users will onboard to Safe with one-click signups using [SafeAuth](https://safe.mirror.xyz/WKxK5FENvkT8BjpowJQAhokYzb22438zUCG3wUSWvjc) and their existing social accounts (Google and Apple) and passkeys (Yubikey and biometrics)

### Networks

#### Bitcoin (P0)
- Some Bitcoin Taproot transactions (txns) aren't fully tracked
- Inflow: 1 large inflow and 1 smaller inflow from separate addresses
- Workaround: Edit untracked outflow to Transfer

#### Gnosis Chain DAI (P1)
High usage for payments

#### Arweave AR (P1)
High usage with developers for app storage

### Centralized exchanges CEXs

#### Ledn API (P1)
- The only centralized exchange lending provider in North America to survive the liquidation events of 2022
- CSV exports contain duplicate internal transfer transactions that can be removed with a direct API integration

### Staking protocols

#### Chainlink staking (P2)
Track Chainlink (LINK) staking deposits, withdrawals, and rewards

### Transaction types

#### Multiple in multiple out (MIMO) (P1 | Ticket 190737)
- About: Important for organizations and advanced users to batch transactions (txns)
- Expect: Track transfer txns with multiple inputs and multiple outputs as Transfers
- Observe
    - Transfer txns with multiple inputs and multiple outputs are tracked as Trades
    - [Screenshot](https://drive.proton.me/urls/J4C7AYXM0W#5AsGRgSc9QCs)
- Workaround
    - Manually add individual separate Transfer txns for each asset
    - Ignore the original MIMO txn

### Lending tokens

#### Aave (P2)
Auto track earned interest income while holding tokens (e.g. AAVE)

## Onboarding

### Bulk add account addresses (P2)
- Add a list of account addresses
- Adding dozens of addresses across multiple networks can take hours
- Potential solutions
    - Copy and paste UX view
    - CSV upload

### Audit protection plan (P2)
[TurboTax audit protection plan open info (OI)](https://hackmd.io/@openinfo/turbotax/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fturbotax-about#TurboTax-audit-protection)

# Resolved

## Integrations

### Centralized exchanges CEXs

#### Coinbase duplicate transactions (P0)
- Marked as resolved _2021-11-01_
- Transfers from Coinbase wallets: ETH transfers creates 2 separate txns.
  1. Coinbase outflow combining the transfer amount + fee in the amount while showing $0 fee
  2. Wallet inflow with correct amount + fee. This requires creating 1 new manual entry to reflect the amount and fee and ignoring the 2 auto generated events.
- *See [Roadmap > Bugs > Coinbase duplicate transactions](https://feedback.cointracker.io/bugs/p/coinbase-duplicate-transactions)*

### Liquidity pools (LPs)

#### Transfer liquidity pool (LP) cost basis (P2)
- *See [Liquidity transactions on CoinTracker](https://support.cointracker.io/hc/en-us/articles/20897601327505-Liquidity-transactions-on-CoinTracker)*
- Option to transfer the cost basis when depositing into and withdrawing from liquidity pools
- Access setting: Select your profile username (Top-right menubar) > "Settings" > "Tax" tab > "Treat liquidity pool transactions as non-taxable"

<p style="text-align: center; font-style: italic">This is not financial, technical, or legal advice. Do your own research and consult professionals.</p>