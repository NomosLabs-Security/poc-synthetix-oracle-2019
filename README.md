# Synthetix Oracle Manipulation — PoC

> **Educational Purpose Only** — This PoC is created for security research and education
> purposes only. It runs against a fork, not mainnet.

## Quick Start

```bash
git clone https://github.com/NomosLabs-Security/poc-synthetix-oracle-2019
cd poc-synthetix-oracle-2019
forge test -vvvv
```

## Details

- **Exploit Date:** 2019-06-25
- **Fork Block:** #8023563 (one block prior)
- **Expected Output:** Stale oracle feed exploitation for synthetic asset arbitrage
- **Full Analysis:** [NomosLabs Security Intelligence Archive](https://nomoslabs.io/archive/synthetix-oracle-2019)

## Description

A bot exploited a stale KRW (Korean Won) price feed on Synthetix to mint
sKRW at a wildly incorrect rate, then convert to sETH at the correct rate.
The bot made ~$1B in "profit" but Synthetix negotiated a return.

## License

MIT — For educational use only.
