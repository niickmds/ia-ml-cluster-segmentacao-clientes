# Segmentação de clientes com clustering

Mini projeto de IA/ML não supervisionado com EDA e comparação de K-Means, clustering aglomerativo e DBSCAN.

## Autores

- Nicolas Mariano da Silva — RA 00333111
- Pedro Henrique Isamu Fagundes de Souza Tsukahara Yoshissaro — RA 00330820 — [@knutzin](https://github.com/knutzin)

## Notebook

Abra [analise_cluster_clientes.ipynb](analise_cluster_clientes.ipynb) no Jupyter ou Google Colab. O CSV está em [Mall_Customers.csv](Mall_Customers.csv).

## Dataset

**Mall Customer Segmentation Data**, disponibilizado no [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). São 200 registros com variáveis de idade, renda anual, pontuação de gastos e gênero. É didático, não representa clientes reais e acompanha o projeto para permitir execução sem credenciais do Kaggle.

## Como executar

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Abra o notebook e execute as células em ordem a partir da raiz do repositório.

## Referências

- [Dataset no Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- [Clustering — Scikit-learn](https://scikit-learn.org/stable/modules/clustering.html)
