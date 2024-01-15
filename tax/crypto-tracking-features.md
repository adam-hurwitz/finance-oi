---
title: 📊 Crypto tracking features
tags: finance
description: Crypto tracking features
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

<h1 style="text-align: center;">📊 Crypto tracking features</h1>

<p style="text-align: center; 
          font-style: italic;">Features for cryptocurrency portfolio, tax, and accounting apps</a>
</p>

# Team

- Legal, accounting, and crypto expertise
- New feature development
- Customer support
- Technical issue resolution
- Partnerships and investors

# Form generation

- Sales and Other Dispositions of Capital Assets (8949)
- Additional Income and Adjustments to Income (1040)
- TurboTax compatibility 

# Transaction accuracy

- Transfer out
- Transfer in
- Multiple in multiple out (MIMO) asset transactions
- Transaction amount
- Transaction type
- Transaction fee
- Timestamp
- Blockchain explorer links

# Protocols

## Bitcoin

- Hierarchical deterministic (HD) accounts
    - A new address is generated per transaction for security purposes
    - To research: Ledger, Trezor, and other wallet's strategy to accurately track HD accounts
    - Potential solution: Integrate directly with hierarchical deterministic (HD) accounts to pull read-only transaction data, e.g. Ledger and Trezor.
    - *See [What are Hierarchical Deterministic (HD) Wallets?](https://www.ledger.com/academy/crypto/what-are-hierarchical-deterministic-hd-wallets) by Ledger 2022-10-27*
- Layer 2s
    - Lightning network
    - Bitcoin Liquid Network

## Ethereum
    
- Tokens
    - E.g. ERC-20, ERC-721, and etc.
- Staking
    - Actions: Deposit, withdrawal, and earn interest
    - E.g. Lido, Coinbase, Gemini, Binance US, Rocket Pool, and etc.
- Layer 2s
    - Bridges
        - E.g. Hop, Li.Fi, Connext, Across, and etc.
    - Centralized exchange (CEX) integrations
    - Arbitrum
    - Optimism
    - Polygon
    - etc.
- Gasless decentralized exchange (DEX) trades, e.g. Cow Swap

## Other

- Wrapped tokens
    - E.g. Wrapped Ethereum (wETH)
    - Transfer cost basis?
- Arweave
- IPFS
- etc.

# Exchanges

- Coinbase
    - Support for past account structures
        - Coinbase sub-accounts
        - GDAX
        - Coinbase Pro sub-accounts
        - Advanced Trade
- Gemini
- Ledn
- Binance US
- etc.

# Edits

- Save changes made when accounts resync
    - Manual transaction edits
    - Add transaction(s)
    - Delete transaction(s)
- Change history log
    - Useful for debugging
    - Revert changes and/or revert to past versions
    - Can backup and download versions in a CSV format
    - Same CSV format that is supported for imports and exports
- Lock transactions
    - Per tax year and/or source account
- Account source balance tracker
    - Useful for debugging
    - See the balance of an asset(s) leading up to a given transaction from each account source and identify where potential missing transfer outs/ins may have occurred.
- Bulk delete
    - Useful for spam assets received without permission
- Asset price estimate in the edit tool feature
    - Based on the timestamp and account source

# Filters

- Time
- Account address
    - Centralized exchangs (CEX) accounts
    - Externally owned accounts (EOAs)
        - E.g. Ledger, Trezor, MetaMask, and etc.
    - Safe accounts (Formerly Gnosis Safe)
    - Other multisig accounts
- Transaction hash
- Protocol
    - Layer 1 and layer 2 networks
    - E.g. Bitcoin, Ethereum, Arweave, IPFS, Polygon, Arbitrum, Optimism, and etc.
- Asset
    -  Coin, token, or NFT collection
    -  E.g. BTC, ETH, Bored Ape Yacht Club (BAYC), and etc.
- App
    - E.g. Uniswap, Cow Swap, Lido, Rocket Pool, Lens, Farcaster, and etc.
- Source
    - API
    - Manual (UI and/or import)
- Error type
    - E.g. Missing cost basis (MCB)
- Saved filters
    - Save the current filter view to quickly reopen for future usage.

# Optimize

- Accounting method: Highest in first out (HIFO)/Specific ID
- Tax-loss harvest tracking

# CSV support

- Import and export data in the same format
- Detailed error messages
    - Issue type, e.g., Data type, format, and etc.
    - Example(s) of row(s) and column(s)
- Multiple in multiple out (MIMO) asset transactions
    - Separate assets with a delimeter in the field, e.g., `ETH,WETH,WBTC`.

# User support

- Audit protection support
    - E.g. [TurboTax audit protection](https://hackmd.io/RILGfzSiTtSb_Xxtcchn2Q?view#TurboTax-audit-protection)
- User access controls
    - Different levels of customer support
    - Certified public agent (CPA) support
        - Tax lot reports
- Issue tracker
    - Tracker for personal and support team related issues
    - Includes case/ticket #s for support related issues
- Feature roadmap
    - Public
    - Users can vote and comment

# Security

## Multi-factor authentication (MFA)

- Hardware keys
    - FIDO2: Fast Identity Online
- Apps
    - OATH-TOTP: Time-based One-Time Password 

## Backups

- Offline working file backups
- Similar to TurboTax's *.tax* files

## Transfer cost basis across services

- Importing and exporting data across services is not possible because the cost basis cannot be accurately transferred.
- Loss of manual edits required to resolve various issues

# Platforms

- Web
- Desktop: Windows, macOS, and Linux
    - Useful for offline work
- Mobile

# Products

[Crypto tax software open info (OI)](https://docs.google.com/spreadsheets/d/1qAman-MLsDcNRfNIsO6dFsITWoFdZN9fLObmT0hqvM4/edit#gid=0)

<p style="text-align: center; font-style: italic">This is not financial, legal, or technical advice. Do your own research and consult professionals.</p>