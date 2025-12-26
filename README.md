# Kaggle Practice: Titanic - Machine Learning from Disaster

KaggleのTitanicコンペティションにおける学習・検証記録です。
データ分析、特徴量エンジニアリング、そして複数の機械学習モデルを用いたアンサンブル学習を実装しています。

## プロジェクトの目的
- **データ分析の実践**: 欠損値処理やカテゴリ変数のエンコーディングなど、実践的な前処理手法の習得。
- **モデルの比較・検証**: 決定木、ランダムフォレスト、勾配ブースティング、ニューラルネットワークなど、特性の異なるモデルの比較。

## 使用した技術・モデル

### ライブラリ
- **Data Analysis**: Pandas, NumPy, SciPy
- **Visualization**: Matplotlib
- **Preprocessing**: Category Encoders, Scikit-learn
- **Machine Learning**: Scikit-learn, LightGBM, TensorFlow (Keras), SciKeras

### 実装・検証したモデル
- **Decision Tree**: 決定木によるベースラインモデルの作成と構造の可視化
- **Random Forest**: バギングを用いた精度の向上と過学習の抑制
- **Gradient Boosting**: 勾配ブースティング（GBDT）による予測
- **Neural Network**: Kerasを用いた多層パーセプトロン (MLP) の構築
- **Ensemble Learning**: Voting（多数決）や Stacking（スタッキング）を用いた最終的なモデル統合

## ファイル構成
- `titanic_graphs.ipynb`: データの分布や生存率との関係を可視化
- `titanic_DecisionTree.ipynb`: シンプルな決定木
- `titanic_RandomForest.ipynb`: ランダムフォレスト
- `titanic_NN_rev.ipynb`: ニューラルネットワーク
- `titanic_NN_RF_GB.ipynb`: ニューラルネットワーク、ランダムフォレスト、勾配ブースティングを組み合わせたアンサンブル学習
- `requirements.txt`: 実行に必要なライブラリ一覧。
- `train.csv` / `test.csv`: 学習用・テスト用データセット。

## 環境
- Python 3.13.7
- Jupyter Notebook
