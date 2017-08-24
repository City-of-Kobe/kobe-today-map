# kobe-today-map
Kobe Todayのイベント情報を[SPARQLエンドポイント](https://data.city.kobe.lg.jp/sparql)から取得して
ArcGIS Onlineのストーリーマップで表示する実験です。

掲載しているテキストファイル[（kobe_today_sparql.txt）](https://github.com/City-of-Kobe/kobe-today-map/blob/master/kobe_today_sparql.txt)は、SPARQLのクエリです。
本日開催されているイベントのみを抽出し、ストーリーマップで表示するために必要な、タイトル、説明文、画像URL、サムネイルURL、緯度、経度を含んだCSVを生成します。

完成サンプルは[こちら](http://arcg.is/2vX1Zgy)です。
