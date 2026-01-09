Employee Attrition Analysis（離職予測モデル）
Author: Yuu（2025）

This repository contains a personal project using anonymized synthetic data to analyze employee attrition.
本リポジトリは、匿名化サンプルデータを用いた離職予測モデルの個人プロジェクトです。

==================================================

Project Files / プロジェクト構成

Employee-Yuu.ipynb
モデル構築と評価指標_.ipynb
Employee-Yuu.pdf

==================================================

Purpose / 目的

Predict employee attrition and support early intervention.
離職リスクを可視化し、早期対応につなげること。

==================================================

Contents / 分析内容

・離職率の基礎統計と相関分析
・ストレス評価・勤務形態との関係分析
・特徴量エンジニアリング（前処理・One-Hot化など）
・ロジスティック回帰による予測
・Accuracy／Recall／AUC で評価

==================================================

Key Findings / 結果

・ロジスティック回帰が最も安定した性能
・重要特徴量：ストレス評価、職務満足度、月収、リモート頻度
・施策案：柔軟な勤務形態、ストレスケア強化 など

==================================================

Future Work / 今後の改善

・SMOTE でデータバランス調整
・ハイパーパラメータ最適化
・アンサンブル学習
・ダッシュボード化

==================================================

Colab Links / Colab で開く

Employee-Yuu.ipynb

https://colab.research.google.com/github/Yuu13329/employee-attrition-analysis/blob/main/Employee-Yuu.ipynb

==================================================
Note / 備考

All data is synthetic or anonymized.
本データはすべて合成・匿名化データです。
