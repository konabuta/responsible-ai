# Responsible AI Workshop

責任のある AI (Responsible AI) のワークショップのコンテンツです。

## コンテンツ
### Responsible AI Toolkit

オープンソースライブラリ Responsible AI Tookkit を利用して、機械学習モデルのデバッグと機械学習モデルによる意思決定を支援します。

- [環境準備](notebook/0-Setup.ipynb)
- [機械学習モデルをデバッグする](notebook/responsibleaidashboard-automobile-regression-debugging.ipynb)
- [機械学習モデルで意思決定をサポートする](notebook/responsibleaidashboard-house-decision-making.ipynb)


### InterpretML

オープンソースライブラリ InterpretML を利用してモデルの解釈可能性・説明性を導出します。

- [解釈可能性の高い機械学習モデルを構築する](notebook/interpretml-explainable-boosting-machine.ipynb)

## 環境
- Azure Machine Learning の Compute Instance を想定
- Python 開発ツール (VSCode, JupyterLab, JupyterNotebook など一般的なものを想定)
- Miniconda
    - 本ワークショップでは Conda を用いて Python の仮想環境を構築します。


## 事前準備

1. Azure Machine Learning の Compute Instance を起動し、Python 環境を構築

- 手順 [setup.ipynb](setup.ipynb) に従って Compute Instance の起動と Python 環境のセットアップを実行します。


2. GitHub からコードをクローン

Compute Instance や利用している開発ツールからターミナル (Terminal) にアクセスして、本リポジトリをクローンします。

```bash
pwd # 自分のユーザフォルダ /home/azureuser/cloudfiles/code/Users/_username_ にいることを確認
git clone https://github.com/konabuta/responsible-ai
```


## Upcoming

- Differential Privacy
- Confidential ML