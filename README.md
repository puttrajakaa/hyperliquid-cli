# hyperliquid-cli

> hyperliquid · perp · paper

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-3776AB)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

Hyperliquid paper CLI — stub mark, fee, equity.

## Features

- Default venue hyperliquid / BTC
- Built-in perp strategy plus paper mode
- Risk manager with daily-loss kill switch
- OHLCV store and SHA-256 stub candles
- Backtester with fill + fee model
- Click CLI: backtest, paper, status, orders

## Prerequisites

- Python 3.11+
- Git

## Getting Started

```bash
git clone <repo-url>
cd hyperliquid-cli
python -m pip install -e .
python -m hplxcli --help
```

## CLI Usage

```bash
hplxcli backtest --bars 200
# Replay stub candles

hplxcli paper
# Start a paper session

hplxcli status
# Print engine state

hplxcli orders
# List simulated fills
```

## Project Structure

```
hplxcli/
  core/        engine + risk
  strategy/    grid / dca / ema hooks
  exchange/    stub order client
  data/        candles + backtest
  cli.py
tests/
```

## Configuration

See `hplxcli/config.py`.

| Setting | Default | Description |
|---------|---------|-------------|
| `exchange` | `hyperliquid` | Venue id |
| `symbol` | `BTC` | Default pair |
| `strategy` | `perp` | Active strategy |
| `mode` | `paper` | paper or backtest |

## Tests

```bash
python -m pytest -q
```

## Background

Perp Python notes search hyperliquid-cli.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![hyperliquid](https://img.shields.io/badge/hyperliquid-111827?style=flat-square) ![cli](https://img.shields.io/badge/cli-111827?style=flat-square) ![hyperliquid-cli](https://img.shields.io/badge/hyperliquid%20cli-111827?style=flat-square) ![trading-bot](https://img.shields.io/badge/trading%20bot-111827?style=flat-square) ![crypto-trading](https://img.shields.io/badge/crypto%20trading-111827?style=flat-square) ![binance](https://img.shields.io/badge/binance-111827?style=flat-square) ![defi](https://img.shields.io/badge/defi-111827?style=flat-square) ![algorithmic-trading](https://img.shields.io/badge/algorithmic%20trading-111827?style=flat-square)

`hyperliquid` `cli` `hyperliquid-cli` `trading-bot` `crypto-trading` `binance` `defi` `algorithmic-trading` `quantitative-finance` `open-source` `python`

Search: hyperliquid-cli · hyperliquid · perp · paper · Hyperliquid paper CLI — stub mark, fee, equity.

---

<sub>Hyperliquid paper CLI — stub mark, fee, equity.</sub>
