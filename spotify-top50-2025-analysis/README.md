# Spotify Top 50 2025 Analysis

Análise exploratória das 50 músicas mais populares do Spotify em 2025, com foco em streams, artistas, países, gêneros musicais, consistência, viralidade e características sonoras.

## Pergunta central

O que define o sucesso no Spotify em 2025: um hit viral, presença constante no ranking ou domínio de gênero?

## Sobre o projeto

Este projeto analisa as 50 músicas mais tocadas do Spotify em 2025. A análise busca entender quais artistas, países e gêneros dominaram o ranking, além de comparar volume total de streams com consistência de presença no top 50.

Também são explorados casos fora do padrão, como músicas antigas que voltaram a aparecer entre as mais ouvidas, mostrando como fatores externos podem influenciar o comportamento de consumo musical.

## Objetivos

- Explorar a estrutura do dataset
- Identificar artistas com maior volume total de streams
- Comparar artistas com muitos hits versus artistas com poucos hits muito fortes
- Analisar a presença de países no ranking
- Avaliar o desempenho de diferentes gêneros musicais
- Investigar características sonoras como danceability, energy e valence
- Identificar outliers e casos especiais no ranking
- Comunicar os principais insights de forma clara e visual

## Dados utilizados

O dataset contém informações sobre as 50 músicas mais populares do Spotify em 2025, incluindo:

- Música
- Artista
- País do artista
- Gênero
- Total de streams
- Ano de lançamento
- Danceability
- Energy
- Valence
- Outras características musicais

Fonte: [Kaggle, Spotify Wrapped 2025 Top Songs and Artists](https://www.kaggle.com/)

## Estrutura do projeto

```text
spotify-top50-2025-analysis/
├── 01_exploracao.ipynb
├── 02_volume_vs_consistencia.ipynb
├── 03_generos
├── 04_outliers.ipynb
└── 2025_top50_songs.csv
```

## Notebooks

| Notebook | Descrição |
| :--- | :--- |
| `01_exploracao.ipynb` | Carregamento do dataset, inspeção inicial, análise de países, artistas, gêneros e distribuição dos dados |
| `02_volume_vs_consistencia.ipynb` | Comparação entre volume total de streams e quantidade de músicas por artista |
| `03_generos` | Análise de gêneros musicais, eficiência por gênero e características sonoras |
| `04_outliers.ipynb` | Investigação de casos fora do padrão, incluindo músicas antigas que voltaram ao ranking |

## Principais achados

- Sabrina Carpenter lidera em volume total de streams, com 5,24 bilhões distribuídos em 4 músicas
- Lady Gaga e Bruno Mars se destacam em eficiência, com alto volume de streams em uma única faixa
- Os Estados Unidos representam a maior parte dos artistas presentes no top 50
- Pop e K-Pop aparecem como gêneros fortes em energia e dançabilidade
- Gêneros como Alternative e Art Pop apresentam perfis sonoros diferentes, com menor energia média
- A presença de músicas antigas no ranking mostra o impacto de mídia, nostalgia e viralização
- O caso de "Running Up That Hill", de Kate Bush, mostra como uma música lançada décadas antes pode voltar ao topo por influência cultural
- Mesmo a música menos ouvida do top 50 ainda representa um grande fenômeno global de streaming

## Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Principais habilidades aplicadas

- Leitura e exploração de dados
- Análise exploratória
- Agrupamentos por artista, país e gênero
- Comparação entre volume e consistência
- Identificação de outliers
- Análise de métricas musicais
- Visualização de dados
- Storytelling com dados

## Como executar

1. Clone este repositório:

```bash
git clone https://github.com/dariojunio/projects-data-analysis.git
```

2. Acesse a pasta do projeto:

```bash
cd projects-data-analysis/spotify-top50-2025-analysis
```

3. Abra os notebooks no Jupyter:

```bash
jupyter notebook
```

4. Execute os arquivos na ordem:

```text
01_exploracao.ipynb
02_volume_vs_consistencia.ipynb
03_generos
04_outliers.ipynb
```

## Conclusão

A análise mostra que o sucesso no Spotify pode acontecer de formas diferentes. Alguns artistas dominam pelo volume acumulado de várias músicas no ranking, enquanto outros alcançam grande impacto com apenas uma faixa extremamente forte.

Além disso, o ranking evidencia o peso da indústria musical norte-americana, a força comercial do Pop e do K-Pop, e a influência de fatores externos, como séries, redes sociais e nostalgia, na volta de músicas antigas ao consumo global.
