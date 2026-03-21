# European Basketball & FIBA Historical Closing Odds Dataset (2008–2026)

**63,290 matches · 18 seasons · Decimal format · ML-ready**

Free 50-row structural sample. Full dataset available on [Gumroad](https://sportsdataolivier.gumroad.com/l/hswnlg).

---

## Dataset specifications

| Field | Value |
|---|---|
| Total matches | 63,290 |
| Seasons | 2008/2009 → 2025/2026 |
| Odds type | Closing odds (Decimal format) |
| Missing values | 0 |
| Separator | Semicolon (`;`) |
| Encoding | UTF-8 |

---

## League coverage

| Scope | Leagues |
|---|---|
| International | Euroleague, Eurocup, Basketball Champions League, Eurochallenge |
| Spain | Liga Endesa / Primera FEB |
| Italy | Lega A / Serie A2 |
| Turkey | BSL Super Lig |
| Germany | BBL |
| France | Betclic Elite / Pro B |
| Greece | Basket League |
| Balkans | ABA League |
| Benelux | BNXT League |
| Australia | NBL |

---

## Columns

| Column | Description |
|---|---|
| `Country` | Country where the match was played |
| `League` | League identifier |
| `Season` | Academic basketball season (e.g. 2024/2025) |
| `Date` | Official match date |
| `Type` | Match phase: Regular Season, Play Offs, or Qualification |
| `Home_Team` | Name of the home team (normalized across 18 years) |
| `Home_Points` | Final points scored by the home team |
| `Away_Points` | Final points scored by the away team |
| `Away_Team` | Name of the away team (normalized across 18 years) |
| `Note` | Special condition: OT (Overtime) or empty |
| `Odds_Home` | Closing odds for the home team to win (Decimal format) |
| `Odds_Away` | Closing odds for the away team to win (Decimal format) |
| `End_Of_RT` | Result at end of regular time: Home, Away, or Draw |
| `Number of Points - TOTAL` | Combined score of both teams |
| `Number of Points - INTERVAL` | Categorical bin of total points scored |
| `Winning Margin` | Point differential between winning and losing team |

---

## Key engineering specifics

**Primary key stability:** Club names are fully normalized across 18 years regardless of sponsor changes — Kirolbet Baskonia, Cazoo Baskonia, and Saski Baskonia are all mapped to a single consistent key. Zero additional mapping required.

**COVID-19 documentation:** The 2019/2020 Serie A2 Italian season was cancelled and purged by the Federation. This dataset reflects that historical reality without extrapolating fake data.

---

## Quickstart

```python
import pandas as pd

df = pd.read_csv('Sample_European_Basketball_and_Australia.csv', sep=';')

print(df.shape)
# (50, 16)

print(df.isnull().sum().sum())
# 0

print(df.head())
```

---

## EDA notebook

Full exploratory analysis — schema, missing values, league coverage, odds distribution,
implied probability validation, and XGBoost feature matrix example:

[kaggle.com/code/oliviersportsdata/european-basketball-fiba-closing-odds-18-seasons](https://www.kaggle.com/code/oliviersportsdata/european-basketball-fiba-closing-odds-18-seasons)

---

## Full dataset

The complete 63,290-match archive is available here:

[sportsdataolivier.gumroad.com/l/hswnlg](https://sportsdataolivier.gumroad.com/l/hswnlg)

---

## License

This sample is released for research and educational purposes.  
Redistribution or resale of the purchased full dataset is strictly prohibited.

---

*Olivier Vignez — Sports Betting Data Engineer*  
[sportsdataolivier.gumroad.com](https://sportsdataolivier.gumroad.com)
