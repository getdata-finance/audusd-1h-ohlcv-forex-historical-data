# AUDUSD 1h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-88_034_rows-blue)](https://getdata.finance/datasets/audusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/audusd)

### -> [**Download the full AUDUSD dataset on getdata.finance**](https://getdata.finance/datasets/audusd)

**AUDUSD 1h OHLCV forex historical data** — ultra high-quality 1h OHLCV for **Australian Dollar / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **Australian Dollar / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/audusd) · **88,034** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `AUDUSD_1h.csv` (3,162 rows, `2026-03-12` -> `2026-09-11`, 325.95 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/audusd)** — **88,034** `1h` rows (full `1m`: 5,263,475), **11 timeframes**, `2012-06-24` -> `2026-09-11`.

## Download sample

**[AUDUSD_1h.csv](https://github.com/getdata-finance/audusd-1h-ohlcv-forex-historical-data/blob/main/AUDUSD_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/audusd-1h-ohlcv-forex-historical-data/main/AUDUSD_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/audusd-1h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/audusd-1h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/audusd-1h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/audusd](https://getdata.finance/datasets/audusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/audusd))** |
|---|--:|---|
| Instrument | Australian Dollar / US Dollar · Forex | Australian Dollar / US Dollar · Forex |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 3,162 | **88,034** |
| Size | 325.95 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Period | `2026-03-12` -> `2026-09-11` | `2012-06-24` -> `2026-09-11` |
| File | `AUDUSD_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Coverage report | — | [AUDUSD coverage](https://getdata.finance/coverage/audusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/audusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/audusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUDUSD_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T03:00:00+00:00 | 0.736 | 0.73626 | 0.73533 | 0.73619 | 7863 |
| 2026-03-12T04:00:00+00:00 | 0.73619 | 0.73624 | 0.73483 | 0.73489 | 5928 |
| 2026-03-12T05:00:00+00:00 | 0.73489 | 0.73596 | 0.73452 | 0.73479 | 12049 |
| 2026-03-12T06:00:00+00:00 | 0.73479 | 0.73548 | 0.73366 | 0.73502 | 10435 |
| 2026-03-12T07:00:00+00:00 | 0.73502 | 0.73616 | 0.73458 | 0.73597 | 9586 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T16:00:00+00:00 | 0.71732 | 0.71781 | 0.71728 | 0.71754 | 9605 |
| 2026-09-11T17:00:00+00:00 | 0.71754 | 0.71769 | 0.71724 | 0.71746 | 6617 |
| 2026-09-11T18:00:00+00:00 | 0.71746 | 0.71756 | 0.717 | 0.71729 | 6680 |
| 2026-09-11T19:00:00+00:00 | 0.71729 | 0.71746 | 0.71713 | 0.71724 | 5679 |
| 2026-09-11T20:00:00+00:00 | 0.71724 | 0.7173 | 0.71665 | 0.7167 | 2081 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUDUSD_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUDUSD_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AUDUSD_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **AUDUSD** archive on **[getdata.finance](https://getdata.finance/datasets/audusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **88,034** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full AUDUSD dataset on getdata.finance](https://getdata.finance/datasets/audusd)**

---
*GetData · AUDUSD 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/audusd)*
