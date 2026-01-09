Employee Attrition Analysis（離職予測モデル）

Author: Yuu (2025)

This repository contains a personal machine learning project using anonymized synthetic data to analyze employee attrition.
本リポジトリは、匿名化された合成データを用いた離職予測モデルの個人プロジェクトである。

Project Structure / プロジェクト構成

・Employee-Yuu.ipynb：Main analysis notebook
・Employee-Yuu.pdf：Notebook export (PDF)

Purpose / 目的

Predict employee attrition and support early intervention.
離職リスクを可視化し、早期対応につなげることを目的とする。

Contents / 分析内容

・基礎統計量と相関分析
・ストレス評価・勤務形態との関係分析
・前処理・特徴量エンジニアリング（One-Hot Encoding など）
・ロジスティック回帰による離職予測
・Accuracy / Recall / AUC によるモデル評価

Key Findings / 結果

・ロジスティック回帰は安定した性能を示した
・重要特徴量：ストレス評価、職務満足度、月収、リモート頻度
・示唆：柔軟な勤務形態やストレスケア施策の重要性

Future Work / 今後の改善

・SMOTE によるクラス不均衡対応
・ハイパーパラメータ最適化
・アンサンブル学習の導入
・ダッシュボードによる可視化

Open in Colab / Colabで開く
https://colab.research.google.com/github/Yuu13329/employee-attrition-analysis/blob/main/Employee-Yuu.ipynb

Note / 備考

All data used in this project is synthetic or anonymized.
本プロジェクトのデータはすべて合成または匿名化されたものである。
