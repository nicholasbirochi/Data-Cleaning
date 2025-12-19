# DataClean — Customer Data Cleaning & Preprocessing (Jupyter Notebook)

End-to-end data cleaning and preprocessing of a customer purchase dataset using **Pandas** (with **NumPy**, **Matplotlib/Seaborn**, and **scikit-learn**)—all inside a **Jupyter Notebook**.

## What this project covers

- **Data validation** (schema sanity checks, types, ranges)
- **Cleaning**
  - type fixes and standardization
  - multi-format **date parsing** and normalization
  - **missing-value handling** (rule-based imputation)
  - **duplicate** detection/removal
  - basic **outlier checks**
- **Feature engineering**
  - time-based features derived from `data_compra` (e.g., year/month/day-of-week, depending on your notebook step)
- **Scaling & encoding (final step)**
  - **Min-Max normalization** (0–1) for numeric columns (e.g., `idade`, `renda_anual`, `valor_compra`)
  - **One-Hot Encoding** for categorical columns (e.g., `genero`, `categoria_produto`, `regiao`)

## Dataset

A small customer dataset (CSV) located at:

- `data/dados_clientes.csv`

Example columns:

- `id_cliente`, `nome`, `idade`, `genero`, `renda_anual`, `categoria_produto`, `valor_compra`, `data_compra`, `regiao`

## Output

After running the notebook end-to-end, it generates a preprocessed dataset (normalized + encoded):

- `data/dados_clientes_preprocessados.csv`

## How to run

1. Create and activate a virtual environment.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook
   ```
4. Execute `tratamento_dados_atualizado.ipynb` from top to bottom.

## Project structure

```
33 - DataClean Data Cleaning/
  ├─ tratamento_dados_original.ipynb
  ├─ tratamento_dados.ipynb
  ├─ tratamento_dados_atualizado.ipynb
  └─ data/
     └─ dados_clientes.csv
```

Made with 💜 by Rocketseat.
=======
# DataClean
End-to-end customer data cleaning in a Jupyter Notebook using Pandas: validation, type fixes, date parsing/standardization, missing-value handling, deduplication, outlier checks, and time-based features. Made with 💜 by Rocketseat.