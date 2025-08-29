# Nuxt Minimal Starter

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
# リアルタイム・ロケーション共有＆イベント通知アプリ

## プロジェクト概要

このアプリは、**Nuxt.js 3** を使用して開発された、**リアルタイム・ロケーション共有＆イベント通知アプリ**です。ユーザーは現在地をリアルタイムで共有したり、特定のエリアでプッシュ通知を受け取ったりすることができます。アジャイル開発手法を採用し、GitHub ProjectsとIssuesを利用して効率的に開発を進めていきます。

## 技術スタック

* **フレームワーク**: Nuxt.js 3
* **言語**: TypeScript
* **テスト**: Vitest
* **地図**: Vue Leaflet
* **開発管理**: GitHub Projects, GitHub Issues

## 環境構築手順

プロジェクトをローカルで動かすための手順は以下の通りです。

```bash
# 1. リポジトリをクローン
git clone [https://github.com/your-username/realtime-location-app.git](https://github.com/your-username/realtime-location-app.git)

# 2. プロジェクトディレクトリに移動
cd realtime-location-app

# 3. 依存関係をインストール
npm install

# 4. 開発サーバーを起動
npm run dev
