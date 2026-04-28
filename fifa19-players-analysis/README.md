# FIFA 19 Player Analysis

Análise exploratória do dataset de jogadores do FIFA 19, com foco em desempenho, potencial, valor de mercado, salários, nacionalidades, clubes e características dos atletas.

## Pergunta central

O que diferencia jogadores de elite dos demais jogadores no FIFA 19, e quais jovens talentos apresentam maior potencial de crescimento?

## Sobre o projeto

Este projeto analisa dados de mais de 18 mil jogadores presentes no FIFA 19. A análise explora atributos técnicos, idade, nacionalidade, clube, overall, potencial, valor de mercado e salário semanal.

O objetivo é entender padrões do dataset, identificar jogadores de destaque e comparar características entre atletas, clubes e grupos específicos.

## Objetivos

- Explorar a estrutura geral do dataset
- Identificar os jogadores com maior overall e maior potencial
- Analisar a distribuição de idade, nacionalidade e pé preferido
- Comparar valor de mercado e salários
- Avaliar clubes com melhores médias de overall
- Encontrar jovens talentos com alto potencial
- Criar visualizações para comunicar os principais insights

## Dados utilizados

O dataset contém informações sobre jogadores do FIFA 19, incluindo:

- Nome
- Idade
- Nacionalidade
- Clube
- Overall
- Potencial
- Valor de mercado
- Salário semanal
- Pé preferido
- Posição
- Atributos técnicos
- Atributos físicos
- Cláusula de rescisão

Fonte: [Kaggle, FIFA 19 Complete Player Dataset](https://www.kaggle.com/datasets/karangadiya/fifa19)

## Estrutura do projeto

```text
fifa19-players-analysis/
├── 01_exploracao.ipynb
├── 02_filtragem.ipynb
├── 03_insights.ipynb
└── 04_graphics.ipynb
```

## Notebooks

| Notebook | Descrição |
| :--- | :--- |
| `01_exploracao.ipynb` | Carregamento do dataset, análise da estrutura, dimensões, tipos de dados, valores ausentes e estatísticas iniciais |
| `02_filtragem.ipynb` | Filtros por nacionalidade, clube, overall e potencial, com foco em subgrupos de jogadores |
| `03_insights.ipynb` | Tratamento de valores monetários, análise de salários, valor de mercado, clubes e conclusões gerais |
| `04_graphics.ipynb` | Visualizações para comunicar os principais padrões encontrados na análise |

## Principais achados

- O dataset possui 18.207 jogadores e 88 colunas
- A média de idade dos jogadores é de aproximadamente 25 anos
- A média de overall é de 66, enquanto a média de potencial é de 71
- A Inglaterra é a nacionalidade com mais jogadores registrados no dataset
- O Brasil aparece entre os países com maior quantidade de jogadores
- A maior parte dos jogadores é destra, representando cerca de 77% do dataset
- Neymar Jr aparece como o jogador mais valioso, avaliado em €118,5 milhões
- Lionel Messi possui o maior salário semanal, com €565 mil por semana
- A Juventus apresenta a maior média de overall entre os clubes analisados
- Kylian Mbappé aparece como o jogador com maior potencial, chegando a 95
- Vinícius Júnior se destaca como um dos jogadores mais jovens entre os atletas com potencial acima de 90

## Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- NumPy
- Jupyter Notebook

## Principais habilidades aplicadas

- Leitura e inspeção de dados
- Análise exploratória de dados
- Tratamento de colunas monetárias
- Conversão de valores em texto para valores numéricos
- Agrupamentos com pandas
- Filtros condicionais
- Ordenação e ranking
- Visualização de dados
- Interpretação de padrões

## Como executar

1. Clone este repositório:

```bash
git clone https://github.com/dariojunio/projects-data-analysis.git
```

2. Acesse a pasta do projeto:

```bash
cd projects-data-analysis/fifa19-players-analysis
```

3. Abra os notebooks no Jupyter:

```bash
jupyter notebook
```

4. Execute os notebooks na ordem:

```text
01_exploracao.ipynb
02_filtragem.ipynb
03_insights.ipynb
04_graphics.ipynb
```

## Conclusão

A análise mostra que o dataset do FIFA 19 permite explorar diferentes dimensões do desempenho de jogadores, desde atributos técnicos até indicadores de mercado.

Os resultados reforçam que jogadores de elite combinam alto overall, alto potencial, salários elevados e grande valor de mercado. Ao mesmo tempo, a análise de jovens talentos mostra como jogadores mais novos com potencial elevado podem representar ativos valiosos dentro do contexto do jogo.

