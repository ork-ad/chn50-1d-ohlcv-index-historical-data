# CHN50 1d OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-521_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full CHN50 dataset on ork.ad**](https://ork.ad/)

**CHN50 1d OHLCV Stock index historical data** — ultra high-quality 1d OHLCV for **China 50 Index**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1d OHLCV** for **China 50 Index** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **521** `1d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `CHN50_1d.csv` (519 rows, `2024-07-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **521** `1d` rows (~0.03 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2024-06-28` → `2026-07-02`.

## Download sample

**[CHN50_1d.csv](https://github.com/ork-ad/chn50-1d-ohlcv-index-historical-data/blob/main/CHN50_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/chn50-1d-ohlcv-index-historical-data/main/CHN50_1d.csv)) · [GitHub Releases](https://github.com/ork-ad/chn50-1d-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/chn50-1d-ohlcv-index-historical-data/](https://ork-ad.github.io/chn50-1d-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | China 50 Index · Stock index | China 50 Index · Stock index |
| Timeframes | `1d` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1d rows | 519 | **521** |
| Size | 0.03 MB | ~0.03 MB |
| Period | `2024-07-02` → `2026-07-02` | `2024-06-28` → `2026-07-02` |
| File | `CHN50_1d.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1d` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1d` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`CHN50_1d.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-07-02T00:00:00Z | 12097.42 | 12226.372 | 12041.36 | 12209.872 | 38244.0 |
| 2024-07-03T00:00:00Z | 12209.872 | 12238.712 | 12134.201 | 12210.702 | 29349.0 |
| 2024-07-04T00:00:00Z | 12210.702 | 12293.353 | 12157.82 | 12166.362 | 26679.0 |
| 2024-07-05T00:00:00Z | 12166.362 | 12213.302 | 11932.289 | 11996.79 | 40903.0 |
| 2024-07-08T00:00:00Z | 11996.79 | 12064.911 | 11964.41 | 11967.92 | 30086.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-26T00:00:00Z | 15838.448 | 15838.448 | 15205.862 | 15404.884 | 188615.0 |
| 2026-06-29T00:00:00Z | 15404.58 | 15462.55 | 15095.05 | 15451.55 | 180314.0 |
| 2026-06-30T00:00:00Z | 15451.55 | 15616.45 | 15339.97 | 15594.46 | 126807.0 |
| 2026-07-01T00:00:00Z | 15594.46 | 15608.46 | 15234.44 | 15355.95 | 93358.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('CHN50_1d.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1D').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('CHN50_1d.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('CHN50_1d.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1D')
print(pf.stats())
```

## Download full data

The complete **CHN50** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **521** rows at `1d`, plus all other timeframes in the same ZIP.

**[→ Get the full CHN50 dataset on ork.ad](https://ork.ad/)**

---
*GetData · CHN50 1d OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*