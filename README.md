# INTC 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-399_105_rows-blue)](https://getdata.finance/datasets/intc) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/intc)

### -> [**Download the full INTC dataset on getdata.finance**](https://getdata.finance/datasets/intc)

**INTC 3m OHLCV us stocks historical data** — ultra high-quality 3m OHLCV for **INTC**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **INTC** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/intc) · **399,105** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `INTC_3m.csv` (16,250 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/intc)** — **399,105** `1m` rows (~27.70 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2011-05-09` -> `2026-07-31`.

## Download sample

**[INTC_3m.csv](https://github.com/getdata-finance/intc-3m-ohlcv-stocks-historical-data/blob/main/INTC_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/intc-3m-ohlcv-stocks-historical-data/main/INTC_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/intc-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/intc-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/intc-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/intc](https://getdata.finance/datasets/intc)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/intc))** |
|---|--:|---|
| Instrument | INTC · US stocks | INTC · US stocks |
| Timeframes | `3m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 16,250 | **399,105** |
| Size | 1.63 MB | ~27.70 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2011-05-09` -> `2026-07-31` |
| File | `INTC_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Coverage report | — | [INTC coverage](https://getdata.finance/coverage/intc) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/intc)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/intc) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`INTC_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T14:30:00+00:00 | 44.93 | 45.53 | 43.97 | 45.27 | 1075 |
| 2026-02-02T14:33:00+00:00 | 45.27 | 45.44 | 44.95 | 45.24 | 772 |
| 2026-02-02T14:36:00+00:00 | 45.24 | 45.82 | 45.24 | 45.71 | 750 |
| 2026-02-02T14:39:00+00:00 | 45.71 | 46.12 | 45.66 | 45.92 | 750 |
| 2026-02-02T14:42:00+00:00 | 45.92 | 46.13 | 45.8 | 45.87 | 668 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:45:00+00:00 | 89.86 | 90.05 | 89.72 | 89.77 | 1078 |
| 2026-07-31T19:48:00+00:00 | 89.77 | 89.97 | 89.33 | 89.42 | 1010 |
| 2026-07-31T19:51:00+00:00 | 89.42 | 89.55 | 89.32 | 89.46 | 858 |
| 2026-07-31T19:54:00+00:00 | 89.46 | 89.51 | 88.63 | 88.68 | 1421 |
| 2026-07-31T19:57:00+00:00 | 88.68 | 88.79 | 88.13 | 88.27 | 1857 |

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

df = pd.read_csv('INTC_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('INTC_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('INTC_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **INTC** archive on **[getdata.finance](https://getdata.finance/datasets/intc)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **399,105** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full INTC dataset on getdata.finance](https://getdata.finance/datasets/intc)**

---
*GetData · INTC 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/intc) · 2026-08-04 UTC*
