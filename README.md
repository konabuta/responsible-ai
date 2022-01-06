# Responsible AI Workshop

責任のある AI (Responsible AI) のワークショップのコンテンツです。Responsible AI Toolbox や InterpretML を用います。

## 機械学習モデルの説明・解釈

オープンソースライブラリ interpret を利用して、機械学習モデルの説明・解釈

- Part0 : [環境準備](notebook/0-Setup.ipynb)
- Part1 : [機械学習モデルをデバッグする](notebook/1-responsibleaidashboard-automobile-regression-debugging.ipynb)
- Part2 : [機械学習モデルで意思決定をサポートする](notebook/2-responsibleaidashboard-house-decision-making.ipynb)
- Part3 : [解釈可能性の高い機械学習モデルを構築する](notebook/3-interpretml-explainable-boosting-machine.ipynb)

## 環境

- Python 開発環境 (JupyterLab, Jupyter Notebook など)
    - Part1 では JupyterLab もしくは Jupyter Notebook をご利用ください。
- Miniconda
- Azure Machine Learning

## 事前準備

1. Azure Machine Learning の Compute Instance を起動

Azure Machine Learning studio の `コンピューティング` から作成します。最低でも CPU 4 コア以上のものを選択してください。

2. GitHub からコードを clone

各開発環境 (JupyterLab, Jupyter) のターミナル (Terminal) にアクセスして、本リポジトリをクローンします。

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