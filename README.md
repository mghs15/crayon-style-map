# crayon-style-map
クレヨン風の地図（地理院の最適化ベクトルタイル用）

* 地図記号なし https://mghs15.github.io/crayon-style-map/
* 地図記号あり https://mghs15.github.io/crayon-style-map/?style=style-with-icon
* 旧 ver（地図記号なしのみ） https://mghs15.github.io/crayon-style-map/index_old.html

※地図記号は、国土地理院の地形図の地図記号を参考に作成しつつ、すべての記号を用意しているわけではありません。
※下の画像は旧 ver のものです。
  
![くれよん地図](https://user-images.githubusercontent.com/40787295/233097542-3fdffa40-4722-4a89-b64e-da6736b4a0b5.png)

* 2024/12/08 `line-pattern` 用の PNG を読み込むのではなく、内部生成する方式に変更。それに伴い、style の `line-pattern` 内に、色の RGB 指定を追加。
* 2023/09/01 Maplibre GL JS へ移行
* 2023/09/18 地図記号追加

## blog
https://qiita.com/mg_kudo/items/69976494b9a95893db11

## reference
* https://docs.mapbox.com/mapbox-gl-js/style-spec/
* https://maplibre.org/maplibre-gl-js/docs/
* https://github.com/gsi-cyberjapan/optimal_bvmap/
