# Análise de Market Basket - Questão 7

![GitHub language count](https://img.shields.io/github/languages/count/joaobrittodev/projeto-integrador?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/joaobrittodev/projeto-integrador?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/license/mit)

> Notebook que realiza análise de Market Basket (Associação) usando o dataset `Market_Basket_Optimisation.csv`.

## Descrição

O notebook implementa um workflow de análise de cestas de compras, incluindo:

- Pré-processamento das transações (formato requerido para Apriori).
- Geração de itemsets frequentes e regras de associação (Apriori).
- Avaliação de métricas como suporte, confiança e lift.
- Possíveis aplicações: recomendações de itens, layout de loja e promoções cruzadas.

## Pré-requisitos

- Python 3.8+
- Bibliotecas: pandas, mlxtend

Instalação rápida:

```bash
pip install pandas mlxtend
```

## Como usar

1. Garanta que `Market_Basket_Optimisation.csv` está na pasta `Questao-7/`.
2. Abra `Q7-Supermercado.ipynb` no Jupyter Notebook ou VS Code.
3. Execute as células para reproduzir o pré-processamento, Apriori e a extração de regras.

## Resultados esperados

- Conjunto de regras de associação com suporte, confiança e lift.
- Insights práticos sobre itens frequentemente comprados juntos.

## Contribuição

1. Faça um fork do repositório.
2. Crie uma branch: `git checkout -b feature-nome`.
3. Faça commits e abra um pull request.

## Licença

Projeto sob licença MIT.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>
