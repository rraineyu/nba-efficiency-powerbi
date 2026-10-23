# NBA 2025-26 Efficiency Dashboard (Power BI)

An interactive Power BI dashboard analyzing 2025-26 NBA player performance

**[View the live dashboard](https://app.powerbi.com/links/x3k65mEB0u?ctid=a8046f64-66c0-4f00-9046-c8daf92ff62b&pbi_source=linkShare)**

*(Note: this is a Power BI Share link — may require sign-in depending on access settings.)*

## What it shows

- **Playmaking vs. Scoring** — scatter plot of points vs. assists, sized by rebounds, colored by position
- **Top Scorers** — ranked bar chart of leading scorers
- **Volume vs. Efficiency** — points vs. true shooting %, sized by a usage proxy, revealing which players score efficiently vs. just take a lot of shots

## Data

Sourced from Basketball-Reference (2025-26 season, per-game stats). True shooting % and usage proxy are computed fields — see `nba_2025_26_player_stats.csv` for the full dataset.

## Tools

Power BI (dashboarding), Python (data cleaning and derived metrics)
