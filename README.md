# Topology-Opt-Bridge

## 作品名
トポロジー最適化を用いた橋の2Dモデルプログラム．
![demo](img/topology.gif)

## 概要
このプログラムは，トポロジー最適化を用いて橋の2Dモデル作成の様子を見る．
トポロジー最適化は，DTU.dkのtopopt.pyを参考にしている．

URL：DTU.dk."Topology optimization codes written in Python"

https://www.topopt.mek.dtu.dk/Apps-and-software/Topology-optimization-codes-written-in-Python

## トポロジー最適化

## プログラムの構成

1. 問題のモデル化．設計の初期化．
2. 目的関数の計算
3. 目的関数の感度分析
4. 設計変数の更新
5. 2~4の操作を収束するまで繰り返す．

## 環境
- ファイル構造
  - bridge_sample.py
    - プログラムが動くか確認．
  
- 実行環境
  - Python 3.8
  - numpy
  - scipy
  - matplotlib
  
## 注意事項
- 変数が何を表しているか理解．

