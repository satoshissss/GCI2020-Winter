# Demand Forecast


## 実行環境
Google Colaboratory

## 結果
#### 順位: 5位
#### `Private LB`: 記録なし, `Public LB`: 記録なし

## やったこと

- 再現性の確保のためにモデルを鋳潰して保存
- 集約特徴理や特徴量削減などといった特徴量エンジニアリング
- あとは、スコアの底上げのためにoputnaでハイパラのチューニング
- (当時の自分が)ノートブックにコメントで解説をいれてました
- 再現性の確保のために準備したモデルはgitに置いてないので必要に応じて、`save_items.txt`内のリンクか、[こちら](https://drive.google.com/file/d/1R_5tHcsnTNqGWRaWwlZoi-dQG1m3wgIv/view?usp=sharing)からダウンロードしてください

## 感想や反省点

- タイタニックの時と比べるとカラムが多くて戸惑った記憶がありますが、その分上で書いていることをやるキッカケになり、そのときの考え方が今でもそのまま役にたってます。



※メモリが足りなくてcolabが再読み込みになった場合はimport library and function(importの部分)を実行後、model training(xgb+lgb+cat)以下から実行してください
