# AnalogClocket

**AnalogClocket** is a simple and practical analog clock **Static Web App**.
It runs as a single HTML file with no server or build steps required.
Open it directly in a browser to see the analog clock and the mini flip-style date display.

## Features

- Simple and practical analog clock UI
- `Static Web App` that works in a **single HTML file**
- No server, no build steps
- Works by opening the local HTML file in a browser
- Ready for static hosting (e.g., GitHub Pages)
- **Low load design**
  - The clock updates only on second boundaries
  - Static elements redraw only on initial render and resize
- Click the GitHub icon at the 30-minute position to open the repository

### Demo

- [https://igapyon.github.io/AnalogClocket/](https://igapyon.github.io/AnalogClocket/)

## Usage

- Open `index.html` directly in a browser
- For GitHub Pages, place the file at the repository root

## Libraries

- SVG.js (CDN, MIT License)

## Maintenance

- When making changes, update the `APP_VERSION` string in `index.html`.

## License

- Apache-2.0

---

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

## メンテナンス

- 変更を加えたときは `index.html` の `APP_VERSION` を更新する

- Apache-2.0
