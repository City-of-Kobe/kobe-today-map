# kobe-today-map
Kobe Todayのイベント情報を[SPARQLエンドポイント](https://data.city.kobe.lg.jp/sparql)から取得して
ArcGIS Onlineのストーリマップで表示する実験です。

掲載しているテキストファイル（kobe-today-sparql.txt）は、SPARQLのクエリです。
ストーリマップで表示するために必要な、タイトル、説明文、画像URL、サムネイルURL、緯度、経度を含んだCSVを生成します。
