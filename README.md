# MathForge JP

これは、[Next.js](https://nextjs.org) プロジェクトです。`create-next-app` を使用して初期化されました。

## プロジェクト概要

MathForge JP は、学生が無料で多様な数学問題に触れ、対戦・創作・議論を通して実力を高められる国内向けオンラインプラットフォームです。

## 開発環境のセットアップ

### 1. 依存関係のインストール

まず、プロジェクトの依存関係をインストールします。

```bash
npm install
```

### 2. 環境変数の設定

Supabaseとの接続には環境変数が必要です。プロジェクトのルートディレクトリに `.env.local` ファイルを作成し、以下の内容で設定してください。

```
NEXT_PUBLIC_SUPABASE_URL="あなたのSupabaseプロジェクトのURL"
NEXT_PUBLIC_SUPABASE_ANON_KEY="あなたのSupabaseプロジェクトのAnon Key"
```

これらの値は、Supabaseダッシュボードの「Project Settings」->「API」で確認できます。

### 3. 開発サーバーの起動

開発サーバーを起動します。

```bash
npm run dev
```

ブラウザで [http://localhost:3000](http://localhost.com:3000) を開くと、アプリケーションが表示されます。

`src/app/page.tsx` を編集することで、ページの内容を更新できます。ファイルを編集すると、ページは自動的に更新されます。

### 4. 問題データの準備

`public/math_problems_lv0.json` ファイルは、問題ライブラリの表示に使用される数学問題のデータを含んでいます。このファイルは、`/Users/sakiharariki/青の数学/math_problems_lv0.json` からコピーされています。

## Next.js について

Next.js の詳細については、以下のリソースを参照してください。

- [Next.js ドキュメント](https://nextjs.org/docs) - Next.js の機能と API について学ぶ
- [Next.js を学ぶ](https://nextjs.org/learn) - インタラクティブな Next.js チュートリアル

[Next.js GitHub リポジトリ](https://github.com/vercel/next.js) もご確認ください。フィードバックや貢献を歓迎します！

## Vercel へのデプロイ

Next.js アプリをデプロイする最も簡単な方法は、Next.js の開発元である [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) を使用することです。

詳細については、[Next.js デプロイメントドキュメント](https://nextjs.org/docs/app/building-your-application/deploying) を参照してください。# E-2
