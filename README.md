# Coordy(コーディー)

学生向けコーデ管理アプリ。Material 3(Material Web)で作った単一HTML(`public/index.html`)。

- ホーム: 今日の一着(服の画像とコメント)
- 服: 一覧・検索・カテゴリ絞り込み・編集・削除
- チャット: 手持ちの服からコーデ相談(端末内で動作)
- アップロード: 写真を縮小してIndexedDBに保存
- ショップ: ほしい物リスト(予算合計・購入済み管理)

データはすべてブラウザ内(IndexedDB)に保存されます。以前の天気連動版は `public/legacy.html` に残してあります。

## デプロイ(Cloudflare Workers)
```
npx wrangler deploy
```
