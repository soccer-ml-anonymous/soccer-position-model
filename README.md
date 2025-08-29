# Identification of Attacking Roles in Soccer Based on Machine Learning

This repository contains code and resources for the paper:  
**"Identification of Attacking Roles in Soccer Based on Machine Learning"**  
Currently under peer review for the *Research Journal of Sports Performance*.

---

本リポジトリは、論文「Identification of Attacking Roles in Soccer Based on Machine Learning」に関連するコードおよび資料を含んでいます。  
現在、『スポーツパフォーマンス研究』誌に査読中です。

---

## 📋 Contents / 内容
- `statsbombから選手個人のW杯のヒートマップを描く3.ipynb`  
  : Player heatmap analysis using StatsBomb data (World Cup)
- `ポジションの判別（教師あり学習）2.ipynb`  
  : Position classification using supervised learning
- `README.md`  
  : This file

---

## 🧭 Execution Order / 実行順序
Please run the notebooks in the following order:
1. **Player Heatmap Analysis (World Cup)**  
   This notebook processes StatsBomb event data to generate individual player heatmaps for World Cup matches. It includes data loading, filtering, and visualization steps.
2. **Position Classification using Supervised Learning**  
   This notebook uses the processed data to train and evaluate a supervised learning model (CNN) for identifying player positions based on heatmap features.

---

## 🛠️ Environment / 実行環境

These notebooks were developed and tested using Google Colab, which provides a pre-configured Python environment in the cloud.  
No local setup is required.

The following libraries are used (all available by default in Colab):

- Python 3.10+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow / keras (for CNN model)

---

本ノートブックは [Google Colab](https://colab.researchす。  
Colabに標準で含まれている以下のライブラリを使用しています：

- Python 3.10以上  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- tensorflow / keras（CNNモデル用）

---

## 🧭 Execution Order  / 実行手順

Please run the notebooks in the following order:

1. **Player Heatmap Analysis (World Cup)**  
   This notebook processes StatsBomb event data to generate individual player heatmaps for World Cup matches. It includes data loading, filtering, and visualization steps.

2. **Position Classification using Supervised Learning**  
   This notebook uses the processed data to train and evaluate a supervised learning model (CNN) for identifying player positions based on heatmap features.

---

以下の順番でノートブックを実行してください：
1. **選手個人のヒートマップ分析（W杯）**  
   StatsBombのイベントデータを用いて、W杯における選手個人のヒートマップを作成します。データの読み込み、フィルタリング、可視化の処理を含みます。
2. **ポジションの判別（教師あり学習）**  
   作成したヒートマップの特徴量を用いて、CNNモデルによる選手ポジションの分類と評価を行います。

## 🚀 How to Run
You can open and run the following notebooks in Google Colab:
- 📊 **Player Heatmap Analysis (World Cup)**  
  [Open in Colab](https://colab.research.google.com/drive/1KqpJNR3HeR0WHxMN4U0QSUSDq0m1zyK8?usp=sharing  
  [Open in Colab](https://colab.research.google.com/drive/1atx6wMqQdPFQD4STPy9t0RTFjS_wG_nF?usp=sharing

## 📄 License
This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

## 📬 Contact
For inquiries: (currently not disclosed)
