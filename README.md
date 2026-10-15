# Real Market Financial Datasets (Exness Conta Zero)

Official real market datasets collected from raw institutional feeds (Exness Conta Zero / Raw Spread) for empirical research, quantitative modeling, microstructure analysis, and algorithmic auditing.

## Repository Contents

| File | Type | Description |
| :--- | :--- | :--- |
| `xauusd_real_exness_dataset.zip` | Archive (`.zip`, ~46 MB) | Consolidated multi-timeframe dataset (M1, M5, M15, H1) for XAU/USD (Gold Spot) captured from live institutional feeds. |
| `xauusdz_h1_real_exness.csv` | Dataset (`.csv`, ~2.2 MB) | Raw uncompressed H1 candles for Gold Spot (`XAUUSDm`/`XAUUSDz`) with timestamp, open, high, low, close, and tick volume. |
| `btcusdz_m1_dataset.zip` | Archive (`.zip`, ~1.7 MB) | High-frequency 1-minute (M1) historical candles for BTC/USD (`BTCUSDz`). |

## Data Specification

- **Broker / Venue**: Exness (Conta Zero / Raw Spread Feed)
- **Timezone**: UTC
- **Features Included**: Timestamp, Open, High, Low, Close, Real/Tick Volume, Spread
- **Intended Use**: Academic and empirical quantitative finance research, non-linear dynamic systems analysis, and execution modeling

## Direct Access (Raw Downloads)

Files can be fetched directly in analysis environments and Colab instances:

```bash
# Download Gold multi-timeframe archive
curl -L -O https://raw.githubusercontent.com/elementaldocaos/gold-dataset/main/xauusd_real_exness_dataset.zip

# Download Gold H1 uncompressed CSV
curl -L -O https://raw.githubusercontent.com/elementaldocaos/gold-dataset/main/xauusdz_h1_real_exness.csv

# Download BTC M1 archive
curl -L -O https://raw.githubusercontent.com/elementaldocaos/gold-dataset/main/btcusdz_m1_dataset.zip
```

---
*Maintained by Sepaul Research &middot; Quantitative Research & Modeling*