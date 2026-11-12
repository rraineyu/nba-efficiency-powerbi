# NBA 2025-26 Efficiency Dashboard 

An interactive Tableau dashboard analyzing 2025-26 NBA player performance

**[View the live dashboard](**https://public.tableau.com/views/NBA2025-2026Dashboard/NBADashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**)**

## What it shows

- **Playmaking vs. Scoring** — scatter plot of points vs. assists, sized by rebounds, colored by position
- **Top Scorers** — ranked bar chart of leading scorers
- **Volume vs. Efficiency** — points vs. true shooting %, sized by a usage proxy, revealing which players score efficiently vs. just take a lot of shots

## Data

Sourced from Basketball-Reference (2025-26 season, per-game stats). True shooting % and usage proxy are computed fields — see `nba_2025_26_player_stats.csv` for the full dataset.

## Tools

Tableau (dashboarding), Python (data cleaning and derived metrics)
