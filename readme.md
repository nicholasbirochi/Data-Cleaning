# DataClean — Customer Data Cleaning with Pandas

A study notebook that follows a customer dataset from its first inspection to a prepared CSV. The cleaning decisions and intermediate outputs stay in the notebook so they can be checked before reusing the result.

## Notebook

Open `tratamento_dados.ipynb`. It contains the checks for missing values, dates, duplicates and outliers, followed by preprocessing and derived date columns.

The input file is `data/dados_clientes.csv`. The last cell writes `data/dados_clientes_preprocessados.csv`; review the preceding outputs and cell order before relying on that export.

## Run locally

```bash
pip install pandas numpy matplotlib seaborn notebook
jupyter notebook
```

Start Jupyter from the repository root and open `tratamento_dados.ipynb`. This repository contains one notebook; no separate “original” or “updated” notebook is required.

## Context

This is a data-cleaning exercise, not a production pipeline. The rules are tied to the supplied dataset and should be reviewed before applying them to another base.

Study reference: Rocketseat.

## License

Original code and documentation are covered by [MIT](license). Source datasets and third-party materials keep their own terms.
