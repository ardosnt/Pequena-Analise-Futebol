# ⚽ Pequena Análise de Futebol

Análise exploratória de dados de um campeonato de futebol utilizando Python e Pandas.

## 📋 Sobre o Projeto

Este projeto realiza uma análise estatística do desempenho de 5 times ao longo de 10 partidas, explorando métricas como vitórias, gols, saldo de gols e pontuação.

## 📊 Times Analisados

| Time | Vitórias | Pontos |
|---|---|---|
| Flamengo | 7 | 23 |
| São Paulo | 6 | 19 |
| Palmeiras | 5 | 18 |
| Santos | 4 | 15 |
| Corinthians | 3 | 11 |

## 🔍 O que é analisado

- Visão geral do DataFrame com todas as estatísticas
- Estatísticas descritivas com `describe()`
- Ranking de desempenho por pontos, vitórias e saldo de gols
- Time com mais vitórias e time com menos vitórias
- Distribuição de gols pró por time
- Correlação entre gols marcados e pontuação (resultado: **0.97** — correlação muito alta)

## 🛠️ Tecnologias

- Python 3.13
- Pandas
- Jupyter Notebook

## 📁 Estrutura

```
Pequena-Analise-Futebol/
│
├── analise_planilha_futebol.ipynb  # Notebook principal
└── dados/
    └── campeonato_futebol.xlsx     # Base de dados
```

## ▶️ Como executar

1. Clone o repositório:
```bash
git clone https://github.com/ardosnt/Pequena-Analise-Futebol.git
```

2. Instale as dependências:
```bash
pip install pandas openpyxl
```

3. Abra o notebook:
```bash
jupyter notebook analise_planilha_futebol.ipynb
```
