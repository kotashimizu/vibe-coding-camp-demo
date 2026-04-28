# プロジェクト概要

Next.js + Supabase + Google認証 + Stripe を使ったWebアプリ。

## スタック

- フロントエンド: Next.js (App Router)
- データベース: Supabase (PostgreSQL)
- 認証: Supabase Auth + Google OAuth
- 決済: Stripe
- デプロイ: Vercel

## よく使うコマンド

- `npm run dev` — 開発サーバー起動
- `npm run build` — ビルド確認
- `npx supabase start` — ローカルSupabase起動（使う場合）

## 環境変数

以下は `.env.local` に入れる。コードに直接書かない。

- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`
- `STRIPE_SECRET_KEY`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`

## 守ってほしいこと

- 環境変数をコードに直接書かない
- `console.log` をそのままコミットしない
- 変更前にどのファイルを編集するか必ず確認する
- 大きな変更をする前に一言確認する
