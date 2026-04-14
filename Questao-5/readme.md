# Diagnóstico de Doenças Cardíacas - Questão 5

![GitHub language count](https://img.shields.io/github/languages/count/joaobrittodev/projeto-integrador?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/joaobrittodev/projeto-integrador?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/license/mit)

> Notebook de análise e modelagem para predizer presença de doença cardíaca usando o dataset `heart_disease_uci.csv`.

## Descrição

Este notebook realiza um pipeline de Machine Learning para classificação de presença/ausência de doença cardíaca. O fluxo inclui:

- Carregamento e inspeção do dataset (colunas como age, sex, cp, trestbps, chol, thalch, etc.).
- Tratamento de valores ausentes e pré-processamento (imputação, encoding, padronização).
- Divisão treino/teste e comparação de modelos clássicos (SVC, RandomForest).
- Avaliação usando métricas de classificação e ROC/AUC.

## Pré-requisitos

- Python 3.8+
- Bibliotecas: pandas, numpy, matplotlib, scikit-learn

Instalação rápida:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Como usar

1. Coloque o arquivo `heart_disease_uci.csv` na pasta `Questao-5/`.
2. Abra `questão_5.ipynb` no Jupyter Notebook ou VS Code.
3. Execute célula a célula para reproduzir o pré-processamento, treinamento e avaliação.

Observações úteis presentes no notebook:
- O dataset contém 920 entradas com colunas como `age`, `sex`, `cp`, `trestbps`, `chol`, `thalch`, `exang`, `oldpeak`, entre outras.
- Há passos para checar valores nulos, estatísticas descritivas e visualizações (head, describe, info).

## Resultados esperados

- Relatórios de classificação (precision/recall/f1) para os modelos testados.
- Curva ROC e valores de AUC para comparação de desempenho.

## Contribuição

1. Faça um fork do repositório.
2. Crie uma nova branch: `git checkout -b feature-nome`.
3. Faça commits descritivos e abra um pull request.

## Licença

Projeto sob licença MIT.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>
=======
# Questao 5
>>>>>>> dce495e074a17018214efc02c0b6d669d47914d8
