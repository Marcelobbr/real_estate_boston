# Case Loft

## Autor
* [Marcelo B. Barata Ribeiro](https://www.linkedin.com/in/marcelobarataribeiro/)

## Estrutura

```bash
.
├── data
│   ├── 01_raw
│   │   ├── valuation_data.csv
│   ├── 02_intermediate
│   ├── ├──data.csv
│   │   03_processed
│   │   ├── ...
│   ├── 04_models
│   │   ├── reg_elasticnet.txt
│   │   ├── ...
│   ├── 05_model_output
│   │   ├── reg_elasticnet.json
│   │   ├── ...
│   ├── 06_reporting
│   │   ├── ...
│   ├── temp
│   │   ├── ...
├── docs
│   ├── ...
├── notebooks
│   ├── 01_exploration_and_cleansing.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_encoding.ipynb
│   ├── 04_split.ipynb
│   ├── 05_model_reg_elasticnet.ipynb
│   ├── 05_model_tree_randomforest.ipynb
│   ├── 05_model_tree_xgboost.ipynb
│   ├── 06_model_selection.ipynb
│   ├── 07_final_model.ipynb
│   ├── 08_econometrics.ipynb  #TO DO
│   ├── question06.ipynb
│   ├── question07_sample_evaluation.ipynb
├── src
│   ├── utils.py
│   ├── c04model
│   │   ├── model.py
├── README.md
└── requirements.txt

4 diretórios, 95 arquivos

```


## Estrutura detalhada

### Notebooks
* 01_exploration_and_cleansing.ipynb
* 02_feature_engineering.ipynb
* 03_encoding.ipynb
* 04_split.ipynb
* 05_model_reg_elasticnet.ipynb
* 05_model_tree_randomforest.ipynb
* 05_model_tree_xgboost.ipynb
* 06_model_selection.ipynb
* 07_final_model.ipynb
* 08_feature_importances_and_econometrics.ipynb
* complexity.ipynb
* question06.ipynb
* question07_sample_evaluation.ipynb

## Requerimentos
Esse projeto usa Python 3.7.5 e os seguintes pacotes devem ser instalados se não estiver usando uma distribuição como Anaconda:

> folium - numpy - pandas - matplotlib - plotly - seaborn - statsmodels - scikit-learn - scipy
shap
bokeh

### Python
Para trabalhar com os arquivos, é necessário ter jupyter notebook instalado (se tiver Anaconda, pode pular esse passo). Para instalar, digite no terminal:
```sh
sudo apt update
pip install jupyter
```