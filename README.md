# Responsible AI Workshop

責任のある AI (Responsible AI) のワークショップのコンテンツです。現在は "機械学習モデルの説明・解釈" のみが対象です。

## 機械学習モデルの説明・解釈

オープンソースライブラリ interpret を利用して、機械学習モデルの説明・解釈

- Part0 : [環境準備](notebook/0-Setup.ipynb)
- Part1 : [Explainable Boosting Machine による解釈性の高いモデル開発](notebook/1-EBM-glassbox.ipynb)
- Part2 : [Gradient Boosting 回帰モデルの SHAP による説明](notebook/2-interpretml-regression.ipynb)
- Part3 : [LightGBM 分類モデルの SHAP による説明と Error Analysis + Azure ML](notebook/3-interpretml-erroranalysis-azureml-exp.ipynb)

## 環境

- Python 開発環境 (Jupyter Notebook, Visual Studio Code など)
- Miniconda
- Azure Machine Learning

## 事前準備

1. Azure Machine Learning の Compute Instance を起動

Azure Machine Learning studio の `コンピューティング` から作成します。最低でも CPU 4 コア以上のものを選択してください。

2. GitHub からコードを clone

各開発環境 (JupyterLab, Jupyter, VScode) のターミナル (Terminal) にアクセスして、本リポジトリをクローンします。

```bash
cd Users/<username> # 自分のユーザフォルダに移動
git clone https://github.com/konabuta/responsible-ai
```

3. conda 環境の作成

[0-Setup.ipynb](notebook/0-Setup.ipynb) に記載のコマンドをターミナル (Terminal) で実行します。Part1, 2, 3 それぞれで必要です。

## Upcoming

- DiCE
- Fairlearn
- Differential Privacy
- Confidential ML