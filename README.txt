# AR風 触って選ぶおみくじ（完成版）

## 構成
- index.html
- omikuji.json

同じフォルダに置いて GitHub Pages / Webサーバへアップロードすれば動きます。

## 操作
- スマホ：カメラを許可 → 手を札に近づける（触った扱いで取れる）
- PC：札をクリックで取れる（カメラなしでもOK）

## 調整ポイント
- 取りやすさ：index.html の HIT_RADIUS（px）を 60→80 にするとさらに甘くなります
- 落下時間：CSS の .card の animation: fall 2s を変更（例 3s）
- 出現頻度：JS の setInterval 2000 を変更
