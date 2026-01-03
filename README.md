# AnalogClocket

AnalogClocket は、単一 HTML で動作するアナログ時計 + ミニフリップ日付の Static Web App です。サーバー不要・ビルド不要で、ブラウザで直接開くだけで動きます。

## 特長
- Static Web App: 単一 HTML で完結し、配布や設置が簡単
- 低負荷: 秒境界で更新し、静的要素は初期描画とリサイズ時のみ再描画
- 日付更新は変化時のみフリップ
- GitHub Pages などの静的ホスティングにそのまま配置可能

## 使い方
- `index.html` をブラウザで直接開く
- GitHub Pages で公開する場合はリポジトリのルートに置くだけ
- 公開先: https://igapyon.github.io/AnalogClocket/

## 調整ポイント
- 日付の大きさ: `DATE_SCALE`
- 日付の位置: `r`（中心からの距離）
- 曜日位置: 日付ブロック内の曜日ラベル位置

## 外部ライブラリ
- SVG.js（CDN）
