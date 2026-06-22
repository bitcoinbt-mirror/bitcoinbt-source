# Contributing to BitcoinBT

Thank you for your interest in contributing to **BitcoinBT (BTCBT)**.

BitcoinBT is a Bitcoin Core v26–based implementation and an independent SHA-256 Proof-of-Work blockchain forked from Bitcoin at block height **903,844**.

The project operates as a public mainnet and welcomes constructive contributions from developers, miners, node operators, and community members.

---

## Project Status

BitcoinBT is under active development and ongoing improvement.

* The chain forked from Bitcoin at **block height 903,844**
* The `main` branch represents the current integration branch
* Consensus-related code is handled conservatively
* Network stability and compatibility are prioritized
* The source code is publicly available for independent review, auditing, and compilation

Not all pull requests may be accepted, especially those that impact consensus rules.

---

## What Contributions Are Welcome

We welcome contributions in the following areas:

* Bug fixes (non-consensus critical)
* Build system improvements
* Documentation improvements
* Test coverage and testing tools
* Performance optimizations that do not alter consensus behavior
* Wallet, RPC, and GUI improvements
* Platform compatibility fixes (Linux, Windows, macOS)
* Node operation and infrastructure improvements

---

## Consensus & Protocol Changes

Changes that affect consensus, mining, difficulty adjustment, block validation, transaction rules, or network behavior are subject to strict review.

Please note:

* Consensus changes require discussion before implementation
* Large protocol-impacting changes may be declined even if technically correct
* Long-term network stability is prioritized

If you are unsure whether your change affects consensus, assume that it does and discuss it first.

---

## Pull Request Process

1. Fork the repository
2. Create a feature branch from `main`
3. Keep commits focused and clearly documented
4. Open a Pull Request against the `main` branch
5. Clearly describe:

   * What the change does
   * Why it is needed
   * Whether it affects consensus (Yes / No)

All code changes should be submitted through Pull Requests.

Direct pushes to the main branch may be restricted.

---

## Coding Style

* Follow existing Bitcoin Core coding conventions where applicable
* Keep changes minimal, readable, and well documented
* Avoid unrelated refactoring in the same Pull Request
* Comment complex logic when necessary

---

## Testing Expectations

* Code should compile successfully
* New functionality should include tests where appropriate
* Consensus-related changes must be tested thoroughly
* Contributors should provide relevant testing information when possible

---

## Reporting Issues & Discussions

* Use GitHub Issues for bug reports and feature requests
* Clearly label issues when possible:

  * Bug
  * Improvement
  * Question
* Use GitHub Discussions for technical discussion, feedback, ideas, and community support
* Avoid publicly disclosing unverified security vulnerabilities

Community participation, independent review, and constructive technical discussion are encouraged.

---

## Security Issues

If you discover a security vulnerability:

* Do NOT open a public issue
* Follow the reporting process described in `SECURITY.md`
* Contact the maintainers privately at **[info@bitcoinbt.xyz](mailto:info@bitcoinbt.xyz)**

---

## License

By contributing to BitcoinBT, you agree that your contributions will be licensed under the MIT License, consistent with the rest of the project.

---

Thank you for helping improve BitcoinBT.
