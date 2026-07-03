# BitcoinBT (BTCBT)

> **Notice**
>
> This repository currently serves as the official public mirror of the BitcoinBT project while the primary GitHub repository is undergoing a GitHub account visibility review.
>
> All source code, releases, documentation, and software published here are official.

---

## Overview

BitcoinBT (BTCBT) is an independent SHA-256 Proof-of-Work blockchain based on Bitcoin Core, originating from the Bitcoin blockchain at block height **903,844**.

The network operates as a live public mainnet with active ASIC mining, real block production, public nodes, a blockchain explorer, mining pool infrastructure, and open-source development.

BitcoinBT is designed for miners, node operators, developers, and the wider community who value traditional Proof-of-Work mining and decentralized blockchain infrastructure.

---

# Network Information

| Parameter | Value |
|------------|-------|
| Name | BitcoinBT |
| Ticker | BTCBT |
| Consensus | SHA-256 Proof-of-Work |
| Fork Height | Bitcoin Block #903,844 |
| First BTCBT Block | #903,845 |
| Block Time | 5 Minutes |
| Difficulty Adjustment | ASERT |
| Maximum Supply | 21,000,000 BTCBT |
| Maximum Block Size | 32 MB |
| P2P Port | 8333 |
| RPC Port | 8332 |

---

# Features

- BitcoinBT Core v3.1.1
- Based on Bitcoin Core v26
- Independent SHA-256 Blockchain
- Live Public Mainnet
- SHA-256 ASIC Mining
- 5 Minute Block Target
- ASERT Difficulty Adjustment
- SegWit Support
- Taproot Support
- Schnorr Signature Support
- Public Mining Pool
- Public Blockchain Explorer
- Windows x64 Qt Wallet
- Default 10 GB Pruned Synchronization
- Optional Full Blockchain Synchronization
- Open Source Development

---

# Current Network Status

| Service | Status |
|----------|--------|
| Mainnet | ✅ Active |
| ASIC Mining | ✅ Active |
| Block Production | ✅ Active |
| Public Explorer | ✅ Online |
| Mining Pool | ✅ Online |
| Pool Statistics | ✅ Online |
| Windows Wallet | ✅ v3.1.1 |
| Source Code | ✅ Public |

---

# Windows Wallet

Official Windows Wallet

https://github.com/bitcoinbt-mirror/bitcoinbt-source/releases/tag/v3.1.1-win64

### Features

- Native Windows x64 build
- Qt graphical wallet
- bitcoinbtd daemon
- bitcoin-cli
- bitcoin-wallet
- Default 10 GB Pruned Mode
- Optional Full Blockchain Mode

SHA256 checksums are published with every release.

Users are encouraged to independently verify downloaded binaries before use.

---

# Build From Source

## Linux

```bash
./autogen.sh
./configure
make -j$(nproc)
```

## Run Node

```bash
./src/bitcoinbtd \
-chain=btcbt \
-datadir=$HOME/.bitcoinbt-mainnet
```

---

# Blockchain Storage

During the first launch of the Qt Wallet, users may choose between:

### Recommended

- Pruned Mode
- Approximately 10 GB storage
- Faster synchronization
- Lower disk usage

### Optional

- Full Blockchain
- Downloads and stores the complete blockchain
- Suitable for full archival nodes

No manual configuration is required.

---

# Official Resources

## Website

https://bitcoinbt.xyz

## Block Explorer

https://explorer.bitcoinbt.xyz

## Mining Pool

stratum+tcp://pool.bitcoinbt.xyz:3333

Pool Statistics

https://pool.bitcoinbt.xyz

## GitHub

https://github.com/bitcoinbt-mirror/bitcoinbt-source

## GitHub Discussions

https://github.com/bitcoinbt-mirror/bitcoinbt-source/discussions

## Telegram

https://t.me/Crypto_BTCBT

## X (Twitter)

https://x.com/BTCBT_BitcoinBT

## Email

info@bitcoinbt.xyz

---

# Documentation

Project documentation is available in the `/docs` directory.

Included documents:

- Historical Project Record
- Mainnet Declaration
- Fork Validation Reports
- Development Notes
- Security Policy
- Contribution Guide

---

# Security

Please review:

- SECURITY.md
- CONTRIBUTING.md
- CODE_OF_CONDUCT.md

before submitting issues or pull requests.

If you discover a security vulnerability, please report it privately:

info@bitcoinbt.xyz

---

# Source Code

BitcoinBT is developed as an open-source project.

Developers are encouraged to inspect, audit, compile, and contribute to the project.

Consensus-related modifications should always be reviewed carefully before deployment on production networks.

---

# License

BitcoinBT incorporates portions of Bitcoin Core released under the MIT License.

This project is distributed under the MIT License.

See the LICENSE file for details.

---

# BitcoinBT Vision

BitcoinBT aims to build a long-term independent Bitcoin ecosystem centered on SHA-256 Proof-of-Work mining, public blockchain infrastructure, and open-source development.

The project is committed to maintaining compatibility with traditional Bitcoin mining hardware while supporting decentralization, transparency, and community-driven innovation.

---

© BitcoinBT (BTCBT)
