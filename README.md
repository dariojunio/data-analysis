# Data Analysis Projects

Personal data analysis portfolio by Dário — turning raw datasets into
actionable insights using Python and pandas.

---

<details>
<summary><strong>Impacto Climático na Agricultura do Sudeste Brasileiro</strong></summary>

<br>

**Central question:** How do climate variations (temperature, rainfall, and drought periods) affect the production of major crops in Southeast Brazil?

An exploratory analysis of agricultural production (2013–2023) for coffee, sugarcane, orange, and corn in the Southeast region, investigating the relationship between climate variables and crop yields across 11 years of data.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset structure, production by crop, climate variable trends and initial correlations |

#### Key Findings

- Sugarcane dominates Southeast production with over 5 billion tons in the period, dwarfing orange (154M tons) and coffee (29M tons)
- Average consecutive dry days (CDD): 53 days, with severe drought peaks in 2020 (62 days) and 2017 (61 days)
- Temperature remained relatively stable (25.7°C average) with only 0.5°C variation across the decade
- Climate variability appears to be increasing in recent years, with CDD fluctuations becoming more pronounced
- Extended drought periods pose direct risks to productivity, especially for climate-sensitive crops like coffee and corn

#### Stack

- Python 3
- pandas
- matplotlib
- Jupyter Notebook

#### Datasets

- **Agricultural Production**: IBGE — Pesquisa Agrícola Municipal (PAM)
- **Climate Data**: ERA5 (ECMWF) for precipitation and CDD, CRU TS for temperature

</details>

---

<details>
<summary><strong>FIFA 19 — Player Analysis</strong></summary>

<br>

**Central question:** What separates elite players from average ones —
and which young talents have the highest ceiling?

An end-to-end exploratory analysis of 18,207 players across 164
nationalities and 651 clubs, covering market value, wages, performance
attributes, and future potential.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset structure, null values, distributions and key statistics |
| 02 | `02_filtragem.ipynb` | Filtering by nationality, club and overall rating — finding patterns within subgroups |
| 03 | `03_insights.ipynb` | Market value parsing, wage analysis, club rankings and cross-referencing attributes |
| 04 | `04_graphics.ipynb` | Visual storytelling — bar charts, scatter plots and comparative visualizations |

#### Key Findings

- The most valuable player is Neymar Jr. (PSG) at €118.5M, but the highest earner is Messi at €565K/week
- Juventus leads all clubs in average overall rating (82.3), followed by Napoli (80.0) and Inter (79.8)
- Only 29 players have a potential above 90 — Mbappé tops the list at 95, with Vinícius Júnior as the youngest on it
- 77% of players are right-footed, a ratio that holds consistently across nationalities and skill levels

#### Stack

- Python 3
- pandas
- matplotlib
- Jupyter Notebook

#### Dataset

Available on [Kaggle — FIFA 19 Complete Player Dataset](https://www.kaggle.com/datasets/chaitanyahivlekar/fifa-19-player-dataset/data).

</details>

---

<details>
<summary><strong>Spotify Top 50 — 2025 Analysis</strong></summary>

<br>

**Central question:** What really defines success on Spotify in 2025 —
a viral hit, consistent presence, or genre dominance?

A four-part analysis of the 50 most streamed songs of 2025, exploring
volume vs. consistency, genre dominance, and outlier cases that reveal
how the streaming market actually works.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset structure, distributions, country and genre breakdown |
| 02 | `02_volume_vs_consistencia.ipynb` | Total streams vs. number of songs — who dominates and how |
| 03 | `03_generos.ipynb` | Genre volume, efficiency and sonic profile (danceability, energy, valence) |
| 04 | `04_outliers.ipynb` | Edge cases — a 1985 song in a 2025 ranking, and what they reveal about streaming |

#### Key Findings

- Sabrina Carpenter leads in total streams (5.24B across 4 songs), but Lady Gaga & Bruno Mars top efficiency with 1.70B from a single track
- The USA accounts for 72% of artists in the top 50 — global streaming remains largely American
- K-Pop/Pop leads in sonic energy and danceability, while Alternative and Art Pop sit at the opposite end
- Kate Bush's "Running Up That Hill" (1985) reached the top 50 in 2025, driven by Stranger Things — a rare case of a song being revived twice by the same franchise
- The gap between the most and least streamed song is only 1.14B, meaning every track here is already a global phenomenon

#### Stack

- Python 3
- pandas
- Jupyter Notebook

#### Dataset

Available on [Kaggle — Spotify Wrapped 2025 Top Songs and Artists](https://www.kaggle.com/datasets/alitaqishah/spotify-wrapped-2025-top-songs-and-artists).

</details>

---

<details>
<summary><strong>Brasileirão Série A — Coaches Analysis (2016–2025)</strong></summary>

<br>

**Central question:** Do coaches who stay longer at a club deliver
better results in the Brasileirão?

A two-part analysis of 3,799 matches across 10 seasons, investigating
the relationship between a coach's tenure and their win rate, with a
focus on the top 5 most successful clubs of the period.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset overview, home advantage analysis and top 5 clubs by wins |
| 02 | `02_aproveitamento_tecnicos.ipynb` | Win rate vs. matches coached, efficiency metric and best coach per club |

#### Key Findings

- Home teams won 47.8% of matches, nearly double the away win rate of 25%, confirming a strong home advantage in Brazilian football
- Coaches with 50+ matches average a 41.2% win rate, compared to 34.4% overall — longer tenures correlate with better results
- Jorge Jesus at Flamengo recorded the highest win rate among top 5 clubs: 78.6% across 28 matches
- Abel Ferreira at Palmeiras combines volume (152 matches) with a 53.3% win rate, the most sustained high performance of the period
- Palmeiras and Flamengo dominate the decade with 210 and 206 wins respectively, well ahead of third-placed Atlético-MG with 164

#### Stack

- Python 3
- pandas
- numpy
- matplotlib
- Jupyter Notebook

#### Dataset

Available on [Kaggle — Campeonato Brasileiro de Futebol](https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol/data).

</details>

---

*More projects with Brazilian public datasets coming soon.*
