# BitcoinBT (BTCBT)

BitcoinBT (BTCBT) is an independent SHA-256 Proof-of-Work blockchain forked from Bitcoin at block height **903,844**.

The BitcoinBT network is currently operating as a live public mainnet with active mining, block production, public nodes, wallet support, explorer infrastructure, and mining pool services.

---

## Network Information

| Parameter             | Value                  |
| --------------------- | ---------------------- |
| Name                  | BitcoinBT              |
| Ticker                | BTCBT                  |
| Consensus             | SHA-256 Proof-of-Work  |
| Fork Height           | Bitcoin Block #903,844 |
| First BTCBT Block     | #903,845               |
| Block Time            | 5 Minutes              |
| Difficulty Adjustment | ASERT                  |
| Maximum Supply        | 21,000,000 BTCBT       |
| Maximum Block Size    | 32 MB                  |
| P2P Port              | 8333                   |
| RPC Port              | 8332                   |

---

## Features

* Bitcoin Core v26 Based
* Independent Public Mainnet
* SHA-256 ASIC Mining
* SegWit Support
* Taproot Support
* Schnorr Signatures
* ASERT Difficulty Adjustment
* Public Mining Pool Infrastructure
* Open Source Development

---

## Current Network Status

* Mainnet: Active
* Mining: Active
* Block Production: Active
* Explorer: Online
* Mining Pool: Online
* Wallet Support: Available

---

## Official Resources

### Website

https://bitcoinbt.xyz

### Block Explorer

https://explorer.bitcoinbt.xyz

### Mining Pool

https://pool.bitcoinbt.xyz

### GitHub Repository

https://github.com/bitcoinbtuser/bitcoinbt-source

### GitHub Discussions

https://github.com/bitcoinbtuser/bitcoinbt-source/discussions

### Telegram

https://t.me/Crypto_BTCBT

### X (Twitter)

https://x.com/BTCBT_BitcoinBT

### Email

[info@bitcoinbt.xyz](mailto:info@bitcoinbt.xyz)

---

## Windows Wallet

Official Windows wallet releases:

https://github.com/bitcoinbtuser/bitcoinbt-source/releases

SHA256 checksums are published with each release.

Users are encouraged to independently verify downloaded binaries before use.

---

## Build From Source

### Linux

```bash
./autogen.sh
./configure
make -j$(nproc)
```

### Run Node

```bash
./src/bitcoinbtd \
-chain=btcbt \
-datadir=$HOME/.bitcoinbt-mainnet
```

---

## Documentation

Project documentation and historical records are available in the `/docs` directory.

Important documents include:

* Mainnet Declaration
* Fork Validation Reports
* Network History
* Development Notes

---

## Security

Please review:

* SECURITY.md
* CONTRIBUTING.md
* CODE_OF_CONDUCT.md

before reporting issues or submitting pull requests.

Security vulnerabilities should be reported privately to:

[info@bitcoinbt.xyz](mailto:info@bitcoinbt.xyz)

---

## Source Code

BitcoinBT is open source.

Developers are encouraged to inspect, review, audit, compile, and contribute to the project through GitHub.

Consensus-related modifications should be reviewed carefully before deployment.

---

## License

BitcoinBT incorporates portions of Bitcoin Core released under the MIT License.

This project is distributed under the MIT License.

See the LICENSE file for details.
