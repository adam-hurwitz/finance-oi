---
title: CoinTracker
tags: cointracker
description: CoinTracker open info (OI)
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

<h1 style="text-align: center;">CoinTracker</h1>

<p style="text-align: center; 
          font-style: italic;">
    <a href="https://cointracker.io" target="_blank">cointracker.io</a>
</p>

# Pricing
- Site: [cointracker.io/tax/{YYYY}/plans](https://www.cointracker.io/tax/2023/plans)
- You can fully test for free
    - View estimated gain/loss and income for all years
    - Connect source accounts and fix errors
- 30 day return: [What is your refund policy?](https://support.cointracker.io/hc/en-us/articles/4413071366161-What-is-your-refund-policy-) *by CoinTracker*
    - "You have not downloaded any tax forms or capital gains CSV files for that tax year"

# Tools

## Filters

### About
- Filters are important for resolving errors and/or missing data
- Helps to narrow down where data is potentially missing or incorrect
- E.g. Missing source, transfer in/out, and/or timestamp discrepancy, etc.

### Filter types
- "Date"
    - E.g., 2023-02-01 to 2023-02-09
- "Type"
    - Transaction type, e.g. "Receive"/"Send", "Buy"/"Sell", "Trade", etc.
- "Wallet"
    - i.e. Account
- "Currency"
    - Assets
    - E.g., BTC, ETH, SAFE, and etc.
- "Sync method"
    - "Manual" (CSV) or "Imported" (API)
- "Status"
    - E.g. "Needs review"

### Opportunities

#### Filter by excluding 1 item in a filter type ([P0](https://hackmd.io/@openinfo/cointracker/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fcointracker-opportunities#Prioritization-key))
- Filter type selects all sub-items by default
- The user can deselect items to narrow down the results
- This is important to narrow down to the relevant transaction view when there are many accounts, e.g. dozens, and/or transactions, e.g. 10s of thousands
- [Screenshot](https://drive.proton.me/urls/R8KHDKT7AG#iIRO31H64s5F)

#### Sort by the highest gain/loss amounts ([P1](https://hackmd.io/@openinfo/cointracker/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fcointracker-opportunities#Prioritization-key))
- Helps prioritizes fixing transactions with the largest impact

#### Network filter ([P2](https://hackmd.io/@openinfo/cointracker/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fcointracker-opportunities#Prioritization-key))
- Assets like ERC-20 tokens can be transacted on multiple networks 
- E.g., Ethereum, Gnosis Chain, Arbitrum, and etc.

#### Apps filter ([P2](https://hackmd.io/@openinfo/cointracker/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fcointracker-opportunities#Prioritization-key))
- Based on smart contract applications
- E.g., Safe, CowSwap, Uniswap, and etc.

## Transaction view
- Understand the movement of assets across linked accounts
- "Outgoing" and "Incoming" columns
- Some platforms only show 1 column for inflows/outflows which makes it hard to visualize the movement of assets across linked accounts

## Automatic tax calculations
- Tax calculations run after making changes to a transaction automatically
- E.g. Adding a missing inflow for a transfer to match an incomplete outflow
    - This can resolve large inaccurate reported gains

## Backup transaction data
- Download tax lot information to use on other platforms without connecting all past sources and fixing issues
- Part of the "Ultra" [2023 plan](https://www.cointracker.io/subscription)

## Tax loss harvesting
- Part of the "Prime" and above [2023 plans](https://www.cointracker.io/subscription)
- Resources
    - [Tax loss harvesting open info (OI)](https://docs.google.com/document/d/1KSB1oBmTzmnwHgQwWwpEhIP6gM1Mc5VrgdJlpNSLebw/edit#heading=h.2gh006qtskub)
    - [2022 Crypto Tax Loss Harvesting Guide](https://www.cointracker.io/blog/the-2020-tax-loss-harvesting-guide) *by CoinTracker*

## Portfolio tracker
Graph with the change in portfolio value over time

## Work with a tax professional

### Find a tax professional
[cointracker.io/connect](https://www.cointracker.io/connect)

### Share with your tax professional
- Part of the "Base" and above [2023 plans](https://www.cointracker.io/subscription)
- Review account
- Download tax reports

## Choose tax strategies

- Access setting: Select your profile username (Top-right menubar) > “Settings” > “Tax” tab
- "Cost basis method"
    - HIFO, LIFO, and LIFO
    - [What options do I have for calculating my capital gains?](https://support.cointracker.io/hc/en-us/articles/4413071356177-What-options-do-I-have-for-calculating-my-capital-gains-)
- "Cost basis tracking"
    - [Cost Basis Tracking: Universal vs. Per Wallet](https://support.cointracker.io/hc/en-us/articles/4413071343889-Cost-Basis-Tracking-Universal-vs-Per-Wallet)
- "Treat liquid staking as non-taxable"
    - [Staking transactions in CoinTracker](https://support.cointracker.io/hc/en-us/articles/19457043708177-Staking-transactions-in-CoinTracker)
- "Treat wrapping as non-taxable"
    - [Wrapped tokens on CoinTracker](https://support.cointracker.io/hc/en-us/articles/19968211474193-Wrapped-tokens-on-CoinTracker)
- "Treat lending as non-taxable"
    - [Lending transactions in CoinTracker](https://support.cointracker.io/hc/en-us/articles/20897621733521-Lending-transactions-in-CoinTracker)
- "Treat liquidity pool transactions as non-taxable"
    - [Liquidity transactions on CoinTracker](https://support.cointracker.io/hc/en-us/articles/20897601327505-Liquidity-transactions-on-CoinTracker)
- "Treat staking rewards as non-taxable"
    - [Staking transactions in CoinTracker](https://support.cointracker.io/hc/en-us/articles/19457043708177-Staking-transactions-in-CoinTracker)

## Dark mode
[October Update: Dark mode and more!](https://feedback.cointracker.io/changelog/october-update-dark-mode-and-more)

# Integrations

## Ethereum virtual machine (EVM) compatible networks
- About: This is useful for many layer 2 (L2) networks
- Enable: "Wallets" view > "Add wallet" > "Ethereum" > Select "Add all other EVM wallets with this address"

## CSV uploads

### About
- Autoconvert format from CSV uploads
    - E.g. Coinbase Pro
- Manually convert format from CSV uploads
    - *See [Importing Transaction Histories to CoinTracker Using CSVs](https://support.cointracker.io/hc/en-us/articles/4413071299729-Converting-transaction-history-CSVs-to-the-CoinTracker-CSV-format)*
    - E.g.
        - Ledn
        - BlockFi
        - FTX US
        - Voyager
        - etc.

### Opportunities

#### Add "Notes" column (P2)
- Useful to add context, transaction hash, and/or exchange's transaction ID

## TurboTax
Generate CSV file(s) to upload

## Decentralized finance DeFi
[Decentralized Finance (DeFi) Guide](https://support.cointracker.io/hc/en-us/articles/4413079083153)

## Coinbase Pro
- *See [How to sync Coinbase Pro to CoinTracker](https://help.cointracker.io/en/articles/5546326-how-to-sync-coinbase-pro-to-cointracker)*
- To research: Coinbase Pro API is no longer accessible through Coinbase?
- Opportunity: Multiple Portfolio support
    - [Coinbase Pro Transfers between Portfolios not being imported](https://feedback.cointracker.io/bugs/p/coinbase-pro-transfers-between-portfolios-not-being-imported)
    - Workaround: Upload CSVs for each "portfolio" sub-account

# Related topics

## Edit
- [How to mark transactions with tags - Setting up your Wallets & Exchanges](https://community.cointracker.io/t/how-to-mark-transactions-with-tags/363)
- [I am missing transactions from a wallet or exchange and/or my balances are incorrect. What should I do?](https://help.cointracker.io/en/articles/5148779-i-am-missing-transactions-from-a-wallet-or-exchange-and-or-my-balances-are-incorrect-what-should-i-do)

## Troubleshooting
- [My cost basis / return / capital gain / market value is incorrect. Why?](https://help.cointracker.io/en/articles/1920360-my-cost-basis-return-capital-gain-market-value-is-incorrect-why)
- [Some of my transactions are missing the cost basis or proceeds. What do I do?](https://help.cointracker.io/en/articles/5149033-some-of-my-transactions-are-missing-the-cost-basis-or-proceeds-what-do-i-do)
- Recover 2FA: [I lost my two-factor authentication device. What do I do?](https://help.cointracker.io/en/articles/2641565-i-lost-my-two-factor-authentication-device-what-do-i-do)

## Investors

### Entities
- [Coinbase Ventures](https://ventures.coinbase.com/)
- [Kraken Ventures](https://www.krakenventures.com/investments)
- Intuit Ventures
- [Accel](https://www.accel.com/relationships)
- General Catalyst
- [Initialized Capital](https://initialized.com/startups/)
- [Ycombinator (YC) 2018](https://www.ycombinator.com/companies/?query=cointracker)

### Resources
- [CoinTracker Raises $100M as Crypto Tax Season Heats Up](https://www.coindesk.com/business/2022/01/27/cointracker-raises-100m-as-crypto-tax-season-heats-up/) *by CoinDesk*

<p style="text-align: center; font-style: italic">This is not financial, technical, or legal advice. Do your own research and consult professionals.</p>