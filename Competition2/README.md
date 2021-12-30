# Home Credit Default Risk

[こちらもタイタニックと同様にKaggleのホームクレジット](https://www.kaggle.com/c/home-credit-default-risk/)に限りなく近いコンペ、Kaggleの方はテーブルが複数あったがこちらは1枚のテーブルしかなかったです.

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

