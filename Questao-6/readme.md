# Regressão sobre California Housing - Questão 6

![GitHub language count](https://img.shields.io/github/languages/count/joaobrittodev/projeto-integrador?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/joaobrittodev/projeto-integrador?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/license/mit)

> Notebook que explora o dataset California Housing (fetch_california_housing) e compara modelos de regressão para prever o valor médio das casas (target).

## Descrição

O notebook carrega o dataset California Housing e executa um pipeline com:

- Engenharia de features (ex.: rooms_per_house, bedrooms_ratio).
- Divisão treino/teste e padronização.
- Treinamento e comparação de modelos: Regressão Linear, XGBoost, Rede Neural (MLPRegressor).
- Avaliação com RMSE e R².

## Pré-requisitos

- Python 3.8+
- Bibliotecas: scikit-learn, pandas, numpy, xgboost

Instalação rápida:

```bash
pip install scikit-learn pandas numpy xgboost
```

## Como usar

1. Abra `Q6-California-Housing.ipynb` ou o notebook presente em `Questao-6/` no Jupyter Notebook ou VS Code.
2. Execute as células para reproduzir pré-processamento, treinamento e avaliação.

## Resultados esperados

- RMSE e R² para cada modelo testado.
- Comparação mostrando qual modelo tem melhor desempenho no conjunto de teste.

## Contribuição

1. Faça um fork do repositório.
2. Crie uma branch: `git checkout -b feature-nome`.
3. Faça commits e abra um pull request.

## Licença

Projeto sob licença MIT.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>
