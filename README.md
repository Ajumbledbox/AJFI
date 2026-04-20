# AJFI
Ajumbledbox File Integrity — local file and directory hashing and integrity utility for Windows

**© 2013-2026 Ajumbledbox. All rights reserved.**

Hash files and folders, compare manifests, validate integrity, and verify copies.
All output stays on your machine. Nothing is transmitted anywhere.

---

## What It Does

- Hash files and folders and save the manifest
- Compare two manifests to find differences
- Validate a manifest against live files to confirm nothing has changed
- Copy files to a destination and verify the copy against the source
- Compare one or two directory trees and view results in-app or as an HTML report
- Keep an on-screen accounting summary for each workflow tab

## Output

All output is saved to `AJFI.output.zip` in the same folder as the AJFI executable.
Nothing is written beside your scanned locations.

Use `File > OPEN OUTPUT FOLDER` in the application to open the output folder directly.

`AJFI.index.txt` in the output folder lists every operation by number, date, workflow, and location.

## Storage Boundary

AJFI is for physically attached local storage.

**Allowed:**
- Internal drives and partitions
- USB and other directly attached storage

**Blocked:**
- Network shares
- Mapped network drives
- UNC paths
- Cloud-backed non-local placeholder files

If AJFI blocks a location, copy the files to a local folder such as `Downloads` and run AJFI again.

---

## Download

Download the latest release from the [Releases](../../releases) page.

Each release includes a SHA256 hash for verification.

---

## Support This Project

If you find AJFI useful, consider supporting development.

### Fiat Donations

[![Ko-fi](https://img.shields.io/badge/Ko--fi-☕-blue)](https://ko-fi.com/ajumbledbox)

**Support via Stripe — quick and easy, no account needed:**

| Amount | Link |
|---|---|
| ☕ Tip $2 | [Buy me a coffee](https://buy.stripe.com/cNi9AMf71fDjdfq7xe7wA00) |
| 🍕 Snacks $5 | [Buy me a snack](https://buy.stripe.com/bJe4gsaQLfDj3EQ6ta7wA01) |
| 💪 Support $25 | [Support the projects](https://buy.stripe.com/8x26oA2kf0Ip1wI2cU7wA02) |

### Crypto Donations

All crypto donations go directly to a personal wallet — no middleman, no fees.

| Asset | Network | Address |
|---|---|---|
| BTC | Bitcoin | `bc1q8tct3jc3v7ankrwsscl4ne6u7vx7uvd6yrc06f` |
| ETH | Ethereum | `0xA084AdDe9D97fc583B4ACc4Da6a132B36a563eCe` |
| SOL | Solana | `6eYC7zSaEpE6W15FWJwhnBqwxUbF8EKPEmHGzqkzroG8` |
| XRP | XRP Ledger | `rJ7xCRV5fJv7fhbHaMUtAFBDwee3k3YRDc` |
| USDC | Solana | `6eYC7zSaEpE6W15FWJwhnBqwxUbF8EKPEmHGzqkzroG8` |
| DOGE | Dogecoin | `DNWe2Xx89fsdBbXSjGFEj3cTjUGeJUzpiC` |
| LTC | Litecoin | `LMb1gPvkeFvoLznGTnA6fT3usHPABDnNcd` |

---

## Contact

- Owner: Ajumbledbox
- Contact: ajumbledbox@outlook.com

---

**© 2013-2026 Ajumbledbox. All rights reserved.**
