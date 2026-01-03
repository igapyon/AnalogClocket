# AnalogClocket

**AnalogClocket** は、シンプルで実用的なアナログ時計の **Static Web App** です。
単一の HTML ファイルだけで動作し、サーバーやビルド工程は不要。
ブラウザで直接開くだけで、アナログ時計とミニフリップ形式の日付表示が動作します。

## 特長

- シンプルかつ実用的なアナログ時計 UI
- **単一 HTML で完結**する `Static Web App`
- サーバー不要・ビルド不要
- ローカルの HTML ファイルをブラウザで開くだけで動作
- 静的ホスティング（GitHub Pages など）にそのまま配置可能
- **低負荷設計**
  - 時計は秒境界でのみ更新
  - 静的要素は初期描画およびリサイズ時のみ再描画
- 30分位置の GitHub アイコンをクリックすると GitHubリポジトリを開く

### デモ

- [https://igapyon.github.io/AnalogClocket/](https://igapyon.github.io/AnalogClocket/)

## 使い方

- `index.html` をブラウザで直接開く
- GitHub Pages で公開する場合は、リポジトリのルートに配置するだけ

## 使用ライブラリ

- SVG.js（CDN 経由、MIT License）

## License

- Apache-2.0
