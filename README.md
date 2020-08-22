# 4th_TellusSatellite
signateコンペ、「The 4th Tellus Satellite Challenge：海岸線の抽出」用のリポジトリ

## インプットデータについて
インプットデータはgithub上に保持するには容量が大きい場合がほとんどなので、ディレクトリ構成ルールだけ定めて、git管理対象外とする

## ディレクトリ構成（[このページを参考に](https://www.st-hakky-blog.com/entry/2017/03/24/140738) 変更可能性あり）
├── LICENSE</br>
├── Makefile           <- Makefile with commands like `make data` or `make train`</br>
├── README.md          <- The top-level README for developers using this project.</br>
├── data</br>
│   ├── external       <- Data from third party sources.</br>
│   ├── interim        <- Intermediate data that has been transformed.</br>
│   ├── processed      <- The final, canonical data sets for modeling.</br>
│   └── raw            <- The original, immutable data dump.</br>
│</br>
├── docs               <- A default Sphinx project; see sphinx-doc.org for details</br>
│</br>
├── models             <- Trained and serialized models, model predictions, or model summaries</br>
│</br>
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),</br>
│                         the creator's initials, and a short `-` delimited description, e.g.</br>
│                         `1.0-jqp-initial-data-exploration`.</br>
│</br>
├── references         <- Data dictionaries, manuals, and all other explanatory materials.</br>
│</br>
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.</br>
│   └── figures        <- Generated graphics and figures to be used in reporting</br>
│</br>
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.</br>
│                         generated with `pip freeze > requirements.txt`</br>
│</br>
├── src                <- Source code for use in this project.</br>
    ├── __init__.py    <- Makes src a Python module</br>
    │</br>
    ├── data           <- Scripts to download or generate data</br>
    │   └── make_dataset.py</br>
    │</br>
    ├── features       <- Scripts to turn raw data into features for modeling</br>
    │   └── build_features.py</br>
    │</br>
    ├── models         <- Scripts to train models and then use trained models to make</br>
    │   │                 predictions</br>
    │   ├── predict_model.py</br>
    │   └── train_model.py</br>
    │</br>
    └── visualization  <- Scripts to create exploratory and results oriented visualizations</br>
        └── visualize.py</br>
