# Identification of Attacking Roles in Soccer Based on Machine Learning　　
サッカーにおける機械学習による攻撃時の選手ポジション判別


This repository contains code and resources for the paper:  
**"Identification of Attacking Roles in Soccer Based on Machine Learning"**  
Currently under peer review for the *Research Journal of Sports Performance*.

本リポジトリは、論文「Identification of Attacking Roles in Soccer Based on Machine Learning」に関連するコードおよび資料を含んでいます。  
現在、『スポーツパフォーマンス研究』誌に査読中です。

---

## Research Overview / 研究概要

This repository is part of a research project on identifying attacking roles in soccer using machine learning. Using StatsBomb's FIFA World Cup event data, we visualize player heatmaps and build supervised classification models to detect positional roles. The goal is to enhance tactical analysis and player evaluation through data-driven approaches in sports analytics.

本リポジトリは、サッカーにおける攻撃時の選手ポジション判別に関する研究の一環として作成されたものです。StatsBombが提供するFIFAワールドカップのイベントデータを用いて、選手のヒートマップ可視化および教師あり学習によるポジション分類モデルの構築を行っています。本研究は、戦術分析や選手評価の高度化を目的とし、スポーツデータサイエンスの発展に寄与することを目指しています。

## 📋 Contents / 内容
- `heatmap_wc_statsbomb.py`  
  : Player Pass heatmap analysis using StatsBomb data (World Cup)  
    選手のパスヒートマップをStatsbombデータから描く
- `position_classification_supervised.py`  
  : Position classification using supervised learning  
    教師あり学習によるポジション判別
- `README.md`  
  : This file

## Data Source / データソース
This project uses publicly available data from the [StatsBomb Open Data repository](https://github.com/statsbomb/open-data/).  
Note: According to StatsBomb's terms and conditions, if you publish, share, or distribute any research or insights based on this data, you should state the data source as StatsBomb and use their logo, available in the Media Pack.

本研究では、[StatsBomb Open Data](https://github.com/statsbomb/open-data/)で公開されているFIFAワールドカップのイベントデータを使用しています。  
※本リポジトリはStatsBombのオープンデータを用いた研究成果を含みます。公開・共有にあたっては、StatsBombをデータソースとして明記し、Media Packに含まれるロゴの使用が推奨されています。
<img width="5885" height="943" alt="SB - Icon Lockup - Colour positive" src="https://github.com/user-attachments/assets/0d5aa890-4b0c-4bcd-9b93-e4be5dfdb51a" />

## 🧭 Execution Order / 実行順序
Please run the notebooks in the following order:
1. **Player Heatmap Analysis (World Cup)**  
   This notebook processes StatsBomb event data to generate individual player heatmaps for World Cup matches. It includes data loading, filtering, and visualization steps.
2. **Position Classification using Supervised Learning**  
   This notebook uses the processed data to train and evaluate a supervised learning model (CNN) for identifying player positions based on heatmap features.

以下の順番でノートブックを実行してください：
1. **選手個人のヒートマップ分析（W杯）**  
   StatsBombのイベントデータを用いて、W杯における選手個人のヒートマップを作成します。データの読み込み、フィルタリング、可視化の処理を含みます。
2. **ポジションの判別（教師あり学習）**  
   作成したヒートマップの特徴量を用いて、CNNモデルによる選手ポジションの分類と評価を行います。

## 🛠️ Environment / 実行環境

These notebooks were developed and tested using Google Colab, which provides a pre-configured Python environment in the cloud.  
No local setup is required.  
これらのNotebookは、Google Colab上で開発・検証されています。Google Colabはクラウド上に事前構成されたPython環境を提供しており、ローカル環境でのセットアップは不要です。

The following libraries are used (all available by default in Colab):  
以下のライブラリを使用しています（すべてColabに標準で含まれています）：

- Python 3.10+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow / keras (for CNN model)

## How to Run on Google Colab / 実行方法　（Google Colab）
Click the link below to view the notebook on Google Colab.
Note: The notebook opens in viewer mode. To run the code, please copy it to your own Colab environment.  
以下のリンクをクリックすると、Google Colab上でNotebookを閲覧できます（※閲覧者モードのため、実行にはコピーが必要です）。

- 📊 **Player Heatmap Analysis (World Cup)**  
  [Open in Colab](https://colab.research.google.com/drive/1KqpJNR3HeR0WHxMN4U0QSUSDq0m1zyK8?usp=sharing
- 📊  **Position Classification using Supervised Learning**  
  [Open in Colab](https://colab.research.google.com/drive/1atx6wMqQdPFQD4STPy9t0RTFjS_wG_nF?usp=sharing

## 📄 License
This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

## 📬 Contact
For inquiries: (currently not disclosed)
