# Coordy(コーディー)

学生向けコーデ提案アプリ。天気・部活/プール/体育の予定・手持ちの服から1週間分のコーデを考えます。単一HTML(`public/index.html`)。

## デプロイ(Cloudflare Workers)
```
npx wrangler deploy
```
`wrangler.jsonc` の静的アセット設定で `public/` を配信します。CloudflareのWorkers Buildsでこのリポジトリを接続すると、pushごとに自動デプロイできます。
