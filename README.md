# XAGUSD 30m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-201_887_rows-blue)](https://getdata.finance/datasets/xagusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xagusd)

### -> [**Download the full XAGUSD dataset on getdata.finance**](https://getdata.finance/datasets/xagusd)

**XAGUSD 30m OHLCV metals historical data** — ultra high-quality 30m OHLCV for **Silver / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **Silver / US Dollar** (Metals)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xagusd) · **201,887** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `XAGUSD_30m.csv` (1,848 rows, `2026-07-07` -> `2026-09-02`, 178.75 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xagusd)** — **201,887** `30m` rows (full `1m`: 5,671,224), **11 timeframes**, `2009-02-24` -> `2026-09-02`.

## Download sample

**[XAGUSD_30m.csv](https://github.com/getdata-finance/xagusd-30m-ohlcv-metals-historical-data/blob/main/XAGUSD_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xagusd-30m-ohlcv-metals-historical-data/main/XAGUSD_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/xagusd-30m-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xagusd-30m-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xagusd-30m-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xagusd](https://getdata.finance/datasets/xagusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xagusd))** |
|---|--:|---|
| Instrument | Silver / US Dollar · Metals | Silver / US Dollar · Metals |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 1,848 | **201,887** |
| Size | 178.75 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Period | `2026-07-07` -> `2026-09-02` | `2009-02-24` -> `2026-09-02` |
| File | `XAGUSD_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Coverage report | — | [XAGUSD coverage](https://getdata.finance/coverage/xagusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xagusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/xagusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAGUSD_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T22:30:00+00:00 | 59.621 | 59.749 | 59.545 | 59.717 | 4904 |
| 2026-07-07T23:00:00+00:00 | 59.717 | 59.931 | 59.68 | 59.897 | 4659 |
| 2026-07-07T23:30:00+00:00 | 59.897 | 59.923 | 59.545 | 59.63 | 3881 |
| 2026-07-08T00:00:00+00:00 | 59.63 | 59.941 | 59.572 | 59.826 | 30225 |
| 2026-07-08T00:30:00+00:00 | 59.826 | 60.273 | 59.78 | 60.073 | 22244 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T00:00:00+00:00 | 63.973 | 64.205 | 63.888 | 63.996 | 13968 |
| 2026-09-02T00:30:00+00:00 | 63.996 | 64.104 | 63.707 | 63.737 | 10374 |
| 2026-09-02T01:00:00+00:00 | 63.737 | 64.036 | 63.623 | 63.806 | 27236 |
| 2026-09-02T01:30:00+00:00 | 63.806 | 63.826 | 63.199 | 63.23 | 18144 |
| 2026-09-02T02:00:00+00:00 | 63.23 | 63.251 | 63.186 | 63.201 | 389 |

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

df = pd.read_csv('XAGUSD_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAGUSD_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAGUSD_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **XAGUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xagusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **201,887** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAGUSD dataset on getdata.finance](https://getdata.finance/datasets/xagusd)**

---
*GetData · XAGUSD 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xagusd)*
