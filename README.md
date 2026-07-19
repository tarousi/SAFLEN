# 🚲 SAFLEN — 自転車安全ナビ

自転車ルートの安全度を緑・黄・赤で色分けして可視化するPWAナビアプリです。

## 🌐 デモ

**[https://ユーザー名.github.io/saflen/](https://ユーザー名.github.io/saflen/)**

## ✨ 機能

- 🗺️ **安全度マップ** — Leaflet.js × OpenStreetMapでリアルな地図表示
- 🟢🟡🔴 **安全度色分け** — ルートを3段階で色分け表示
- 🔽 **スマートフィルター** — 自転車通行可・坂道・交通量で絞り込み
- ⚠️ **危険ポイント警告** — 地図上にアイコンで表示
- 🔀 **3ルート比較** — 安全重視・距離重視・最短から選択
- 📱 **PWA対応** — ホーム画面に追加してアプリとして使える
- 💻 **レスポンシブ** — スマホ・タブレット・PCすべてに対応

## 🚀 GitHub Pagesへの公開手順

1. GitHubで新規リポジトリを作成（名前例：`saflen`、Public）
2. 以下のファイルをすべてアップロード：
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
3. Settings → Pages → Source: `main` / `root` → Save
4. 数分後に `https://ユーザー名.github.io/saflen/` で公開完了

## 📱 スマホでのインストール方法

### iPhone（Safari）
1. Safariでサイトを開く
2. 共有ボタン → 「ホーム画面に追加」

### Android（Chrome）
1. Chromeでサイトを開く
2. メニュー → 「ホーム画面に追加」

## 🛠️ 技術スタック

| 技術 | 用途 |
|------|------|
| HTML / CSS / JavaScript | フロントエンド |
| Leaflet.js v1.9.4 | 地図表示 |
| OpenStreetMap | 地図タイル |
| PWA (Service Worker) | オフライン対応・インストール |
| GitHub Pages | ホスティング |

## 🎨 デザイン

- **カラー** — グリーン (#1a7a3c) を基調に、安全度を緑・黄・赤で表現
- **フォント** — Noto Sans JP
- **UIコンセプト** — フィッツの法則に基づく大きなタップ領域

## 📍 地図の中心

柏市・麗澤大学周辺（緯度 35.8536, 経度 139.9731）

---

© 2026 SAFLEN — 麗澤大学 UI/UX Design
