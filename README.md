# Responsible AI Workshop

責任のある AI (Responsible AI) テクノロジーに関するワークショップのコード集です。

## コンテンツ
### Responsible AI Toolbox

オープンソースライブラリ [Responsible AI Toolbox](https://github.com/microsoft/responsible-ai-toolbox) を利用して、機械学習モデルのデバッグと機械学習モデルによる意思決定を支援します。

- [環境準備](notebook/setup.ipynb)
- [機械学習モデルをデバッグする](notebook/responsibleaidashboard-automobile-regression-debugging.ipynb)
- [機械学習モデルで意思決定をサポートする](notebook/responsibleaidashboard-house-decision-making.ipynb)


### InterpretML

オープンソースライブラリ群 [InterpretML](https://interpret.ml/) を利用してモデルの解釈可能性・説明性を導出します。

- [解釈可能性の高い機械学習モデルを構築する](notebook/interpretml-explainable-boosting-machine.ipynb)

## 環境
- Azure Machine Learning の Compute Instance の利用を想定
    - 他の一般的な Python 環境でもオープンソースの利用の範囲であれば実行可能 (テストは未実施)
- Python 開発ツール (VSCode, JupyterLab, JupyterNotebook など一般的なものを想定)
- Miniconda
    - 本ワークショップでは Conda を用いて Python の conda 仮想環境を構築します。


## 事前準備

1. Azure Machine Learning Workspace の作成
- [クイックスタート: Azure Machine Learning の利用を開始するために必要なワークスペース リソースを作成する](https://docs.microsoft.com/ja-JP/azure/machine-learning/quickstart-create-resources) に従って Azure Machine Learning Workspace を作成します。


2. Azure Machine Learning の Compute Instance を起動し、Python 環境を構築

- 手順 [setup.ipynb](notebook/setup.ipynb) に従って Compute Instance の起動と Python 環境のセットアップを実行します。


3. GitHub からコードをクローン

- Compute Instance や利用している開発ツールからターミナル (Terminal) にアクセスして、本リポジトリをクローンします。

```bash
pwd # 自分のユーザフォルダ /home/azureuser/cloudfiles/code/Users/<username> にいることを確認
git clone https://github.com/konabuta/responsible-ai
```
