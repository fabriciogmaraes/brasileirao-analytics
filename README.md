# ⚽ Brasileirão Analytics 2026

> **PT-BR** | [EN](#-brasileirao-analytics-2026-english)

---

## 🇧🇷 Português

### Sobre o Projeto

Análise completa dos dados do **Brasileirão Série A 2026** utilizando Python. O projeto coleta dados reais via API, constrói métricas de desempenho do zero e transforma tudo em visualizações que contam histórias que a tabela comum não mostra.

Esse é o **primeiro projeto** de um portfólio de analytics esportivo em construção, com atualizações planejadas ao longo da temporada.

---

### 📊 O que foi analisado

| Bloco | Análise | Tipo de Gráfico |
|---|---|---|
| 1 | Tabela de Desempenho Geral | Barras horizontais por zona |
| 2 | Poder Ofensivo | Barras com gradiente |
| 3 | Solidez Defensiva | Barras com gradiente |
| 4 | Saldo de Gols | Barras divergentes |
| 5 | Mando de Campo | Barras agrupadas |
| 6 | Consistência por Rodada | Small Multiples (Top 6) |
| 7 | Probabilidade de Título | Gráfico de Bolhas |

---

### 🛠️ Tecnologias Utilizadas

- **Python 3.13**
- **Pandas** — manipulação e análise de dados
- **Matplotlib** — visualizações
- **Requests** — coleta via API
- **Jupyter Notebook** — desenvolvimento interativo
- **Git/GitHub** — versionamento

---

### 📡 Fonte de Dados

- **[football-data.org](https://www.football-data.org/)** — API gratuita com dados reais do Brasileirão 2026 (resultados, placares, rodadas)

---

### 📁 Estrutura do Repositório

```
brasileirao-analytics/
│
├── coleta_dados.ipynb              # Fase 1: Conexão com API e coleta
├── metricas.ipynb            # Fase 2: Métricas e visualizações
│
├── brasileirao_2026.csv            # Dados brutos coletados
├── tabela_desempenho_2026.csv      # Tabela geral calculada
├── poder_ofensivo_2026.csv         # Ranking ofensivo
├── solidez_defensiva_2026.csv      # Ranking defensivo
├── saldo_gols_2026.csv             # Saldo de gols por time
├── mando_de_campo_2026.csv         # Aproveitamento casa vs fora
├── probabilidade_titulo_2026.csv   # Projeção de título
│
├── tabela_brasileirao_2026.png
├── poder_ofensivo_2026.png
├── solidez_defensiva_2026.png
├── saldo_gols_2026.png
├── mando_de_campo_2026.png
├── consistencia_rodadas_2026.png
├── probabilidade_titulo_2026.png
│
└── README.md
```

---

### 🚀 Como Executar

**1. Clone o repositório**
```bash
git clone https://github.com/fabriciogmaraes/brasileirao-analytics.git
cd brasileirao-analytics
```

**2. Crie um ambiente virtual e instale as dependências**
```bash
python -m venv .venv
.venv\Scripts\activate  # Windows
pip install requests pandas matplotlib jupyter
```

**3. Cadastre-se e obtenha sua API Key**
Acesse [football-data.org](https://www.football-data.org/) e crie uma conta gratuita.

**4. Execute os notebooks em ordem**
```
1. coleta_dados.ipynb
2. metricas.ipynb
```

---

### 📈 Alguns Insights

- **Palmeiras** lidera com 79.2% de aproveitamento e 17 gols marcados em 8 jogos
- **Flamengo** tem o segundo melhor saldo de gols (+8) com um jogo a menos
- **Grêmio** tem 83% de aproveitamento em casa e apenas 8% fora — dois times diferentes
- **Bahia** tem 75% de aproveitamento fora de casa — melhor visitante da competição
- **Cruzeiro** acumula saldo de -8 e 0% de probabilidade de título no ritmo atual

---

### 🔄 Próximas Atualizações

- [ ] Atualização dos dados após cada rodada
- [ ] Versão 2.0 com cartões, faltas e posse de bola (API paga)
- [ ] Análise histórica com 10 anos de dados
- [ ] Dashboard interativo

---

### 👤 Autor

**Fabricio Guimarães**
Analista de BI | Mestrando em Inteligência Computacional — PPgTI/UFRN

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Fabricio_Guimarães-blue?style=flat&logo=linkedin)](https://linkedin.com/in/fabriciogmaraes)
[![GitHub](https://img.shields.io/badge/GitHub-fabriciogmaraes-black?style=flat&logo=github)](https://github.com/fabriciogmaraes)

---
---

## 🌎 English

### About the Project

A complete analysis of **Brasileirão Série A 2026** (Brazilian top football league) using Python. The project collects real data via API, builds performance metrics from scratch, and transforms everything into visualizations that tell stories the regular standings table doesn't show.

This is the **first project** of a sports analytics portfolio under construction, with planned updates throughout the season.

---

### 📊 What Was Analyzed

| Block | Analysis | Chart Type |
|---|---|---|
| 1 | Overall Performance Table | Horizontal bars by zone |
| 2 | Offensive Power | Gradient bars |
| 3 | Defensive Solidity | Gradient bars |
| 4 | Goal Difference | Diverging bars |
| 5 | Home vs Away Performance | Grouped bars |
| 6 | Consistency per Round | Small Multiples (Top 6) |
| 7 | Title Probability | Bubble Chart |

---

### 🛠️ Technologies Used

- **Python 3.13**
- **Pandas** — data manipulation and analysis
- **Matplotlib** — data visualization
- **Requests** — API data collection
- **Jupyter Notebook** — interactive development
- **Git/GitHub** — version control

---

### 📡 Data Source

- **[football-data.org](https://www.football-data.org/)** — free API with real Brasileirão 2026 data (results, scores, matchdays)

---

### 📁 Repository Structure

```
brasileirao-analytics/
│
├── coleta_dados.ipynb              # Phase 1: API connection and data collection
├── metricas.ipynb                  # Phase 2: Metrics and visualizations
│
├── brasileirao_2026.csv            # Raw collected data
├── tabela_desempenho_2026.csv      # Calculated overall table
├── poder_ofensivo_2026.csv         # Offensive ranking
├── solidez_defensiva_2026.csv      # Defensive ranking
├── saldo_gols_2026.csv             # Goal difference per team
├── mando_de_campo_2026.csv         # Home vs away performance
├── probabilidade_titulo_2026.csv   # Title probability projection
│
└── README.md
```

---

### 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/fabriciogmaraes/brasileirao-analytics.git
cd brasileirao-analytics
```

**2. Create a virtual environment and install dependencies**
```bash
python -m venv .venv
.venv\Scripts\activate  # Windows
pip install requests pandas matplotlib jupyter
```

**3. Get your free API Key**
Sign up at [football-data.org](https://www.football-data.org/).

**4. Run the notebooks in order**
```
1. coleta_dados.ipynb
2. metricas.ipynb
```

---

### 📈 Key Insights

- **Palmeiras** leads with 79.2% points ratio and 17 goals in 8 matches
- **Flamengo** has the second-best goal difference (+8) with one match less played
- **Grêmio** wins 83% at home but only 8% away — two completely different teams
- **Bahia** wins 75% of away matches — best away side in the competition so far
- **Cruzeiro** has a -8 goal difference and 0% title probability at current pace

---

### 🔄 Upcoming Updates

- [ ] Data updates after each round
- [ ] Version 2.0 with cards, fouls and possession (paid API)
- [ ] Historical analysis with 10 years of data
- [ ] Interactive dashboard

---

### 👤 Author

**Fabricio Guimarães**
BI Analyst | Master's Student in Computational Intelligence — PPgTI/UFRN

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Fabricio_Guimarães-blue?style=flat&logo=linkedin)](https://linkedin.com/in/fabriciogmaraes)
[![GitHub](https://img.shields.io/badge/GitHub-fabriciogmaraes-black?style=flat&logo=github)](https://github.com/fabriciogmaraes)
