# Data Analysis Projects

Personal data analysis portfolio by Dário, turning raw datasets into actionable insights using Python, pandas and visual analysis.

---

<details>
<summary><strong>Impacto Climático na Agricultura do Sudeste Brasileiro</strong></summary>

<br>

**Central question:** How do climate variations, especially rainfall, temperature and drought periods, relate to agricultural production in Southeast Brazil?

An exploratory analysis of agricultural production from **2013 to 2023** for coffee, sugarcane, orange and corn in Southeast Brazil. The project investigates how climate variables such as precipitation, average temperature and consecutive dry days may help explain production patterns across 11 years of data.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset structure, agricultural production by crop, climate trends and initial exploratory insights |
| 02 | `02_analise_chuva_producao_agricola_sudeste.ipynb` | Relationship between rainfall and agricultural production, with visual analysis of precipitation patterns and crop behavior |

#### Key Findings

- Sugarcane dominates agricultural production in Southeast Brazil, with a much higher total volume than orange, coffee and corn
- Rainfall is an important variable to observe when analyzing agricultural production, but it should not be interpreted in isolation
- Consecutive dry days help identify periods of potential water stress, especially for crops more sensitive to drought
- Temperature remains a relevant climate indicator, even when yearly variation appears smaller than rainfall or drought intensity
- The relationship between climate and production suggests that agricultural performance depends on multiple factors, including weather, crop type, technology, soil, irrigation and management practices

#### Stack

- Python 3
- pandas
- matplotlib
- Jupyter Notebook

#### Datasets

- **Agricultural Production:** IBGE, Pesquisa Agrícola Municipal, PAM
- **Climate Data:** ERA5, ECMWF, for precipitation and consecutive dry days
- **Temperature Data:** CRU TS, Climatic Research Unit

</details>

---

<details>
<summary><strong>FIFA 19 Player Analysis</strong></summary>

<br>

**Central question:** What separates elite players from average ones, and which young talents have the highest ceiling?

An end-to-end exploratory analysis of 18,207 players across 164 nationalities and 651 clubs, covering market value, wages, performance attributes and future potential.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset structure, null values, distributions and key statistics |
| 02 | `02_filtragem.ipynb` | Filtering by nationality, club and overall rating, finding patterns within subgroups |
| 03 | `03_insights.ipynb` | Market value parsing, wage analysis, club rankings and cross-referencing attributes |
| 04 | `04_graphics.ipynb` | Visual storytelling with bar charts, scatter plots and comparative visualizations |

#### Key Findings

- The most valuable player is Neymar Jr. from PSG at €118.5M, while the highest earner is Messi at €565K per week
- Juventus leads all clubs in average overall rating, followed by Napoli and Inter
- Only 29 players have potential above 90, with Mbappé topping the list and Vinícius Júnior standing out as the youngest player in that group
- 77% of players are right-footed, a pattern that remains consistent across nationalities and skill levels

#### Stack

- Python 3
- pandas
- matplotlib
- Jupyter Notebook

#### Dataset

Available on [Kaggle, FIFA 19 Complete Player Dataset](https://www.kaggle.com/datasets/chaitanyahivlekar/fifa-19-player-dataset/data).

</details>

---

<details>
<summary><strong>Spotify Top 50 2025 Analysis</strong></summary>

<br>

**Central question:** What really defines success on Spotify in 2025: a viral hit, consistent presence or genre dominance?

A four-part analysis of the 50 most streamed songs of 2025, exploring volume versus consistency, genre dominance and outlier cases that reveal how the streaming market works.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset structure, distributions, country and genre breakdown |
| 02 | `02_volume_vs_consistencia.ipynb` | Total streams versus number of songs, showing who dominates and how |
| 03 | `03_generos.ipynb` | Genre volume, efficiency and sonic profile, including danceability, energy and valence |
| 04 | `04_outliers.ipynb` | Edge cases, including older songs returning to the charts and what they reveal about streaming behavior |

#### Key Findings

- Sabrina Carpenter leads in total streams with 5.24B across 4 songs, while Lady Gaga and Bruno Mars lead in efficiency with 1.70B from a single track
- The USA accounts for 72% of artists in the top 50, showing that global streaming remains strongly American-centered
- K-Pop and Pop lead in sonic energy and danceability, while Alternative and Art Pop appear on the opposite side of the profile
- Kate Bush's "Running Up That Hill" from 1985 reached the top 50 in 2025, driven by Stranger Things, showing how media can revive older songs
- The gap between the most and least streamed songs is only 1.14B, meaning every track in the ranking is already a global phenomenon

#### Stack

- Python 3
- pandas
- Jupyter Notebook

#### Dataset

Available on [Kaggle, Spotify Wrapped 2025 Top Songs and Artists](https://www.kaggle.com/datasets/alitaqishah/spotify-wrapped-2025-top-songs-and-artists).

</details>

---

<details>
<summary><strong>Brasileirão Série A Coaches Analysis 2016 to 2025</strong></summary>

<br>

**Central question:** Do coaches who stay longer at a club deliver better results in the Brasileirão?

A two-part analysis of 3,799 matches across 10 seasons, investigating the relationship between a coach's tenure and win rate, with a focus on the top 5 most successful clubs of the period.

#### Notebooks

| # | Notebook | What it covers |
|---|---|---|
| 01 | `01_exploracao.ipynb` | Dataset overview, home advantage analysis and top 5 clubs by wins |
| 02 | `02_aproveitamento_tecnicos.ipynb` | Win rate versus matches coached, efficiency metric and best coach per club |

#### Key Findings

- Home teams won 47.8% of matches, nearly double the away win rate of 25%, confirming a strong home advantage in Brazilian football
- Coaches with 50 or more matches average a 41.2% win rate, compared to 34.4% overall, suggesting that longer tenures are associated with better results
- Jorge Jesus at Flamengo recorded the highest win rate among top 5 clubs, with 78.6% across 28 matches
- Abel Ferreira at Palmeiras combines volume, with 152 matches, and a 53.3% win rate, representing the most sustained high performance of the period
- Palmeiras and Flamengo dominate the decade with 210 and 206 wins respectively, well ahead of third-placed Atlético-MG with 164

#### Stack

- Python 3
- pandas
- numpy
- matplotlib
- Jupyter Notebook

#### Dataset

Available on [Kaggle, Campeonato Brasileiro de Futebol](https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol/data).

</details>

---

*More projects with Brazilian public datasets coming soon.*
