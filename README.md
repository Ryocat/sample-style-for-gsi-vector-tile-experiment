「地理院地図Vector（仮称）提供実験」のための.qmlファイル
======================
「[地理院地図Vector（仮称）提供実験](https://maps.gsi.go.jp/development/vt.html)」（[GitHub](https://github.com/gsi-cyberjapan/gsimaps-vector-experiment)）をQGISのベースマップとして利用するためのスタイルファイルのサンプルです。

# 設定手順
1. .qmlファイルをローカルの適当なところに保存する。
2. QGISのブラウザパネルのVector Tilesを右クリック>新規一般接続で `https://cyberjapandata.gsi.go.jp/xyz/experimental_bvmap/{z}/{x}/{y}.pbf` に接続する。レイヤ名を「地理院地図ベクトルタイル」、最大ズームレベルを「18」などと適宜設定する。
3. Vector Tilesに追加された地理院地図ベクトルタイルのレイヤをダブルクリックでプロジェクトに追加する。
4. レイヤパネルでレイヤ名を右クリックし、プロパティ>シンボロジ>スタイル（左下にある）>「スタイルを読み込む」を選択。「ファイルから」を選択してファイルの空欄の右にある「…」をクリックし、手順1で保存した.qmlファイルを選択する。スタイルを読み込む>適用で、レイヤが表示される。
