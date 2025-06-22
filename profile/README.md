# Spot-S System リポジトリ一覧

最終更新: 2025-06-22

## 📊 カテゴリ別リポジトリ

### 🤖 自動化・連携ツール

| リポジトリ | 説明 | 言語 | 最終更新 | ステータス |
|-----------|------|------|----------|------------|
| [officestation-doc-downloader](https://github.com/spot-s-system/officestation-doc-downloader) | 公文書を自動的に取得してGoogleDriveに格納するツール | TypeScript | 2025-06-22 | ✅ Active |
| [stripe-webhook-function](https://github.com/spot-s-system/stripe-webhook-function) | 給与伴走くんのStripeWebhookトリガーでメールを送付するクラウド関数 | TypeScript | 2025-06-16 | ✅ Active |

### 📋 管理システム

| リポジトリ | 説明 | 言語 | 最終更新 | ステータス |
|-----------|------|------|----------|------------|
| [manual-management-system](https://github.com/spot-s-system/manual-management-system) | freeeの操作ガイドを管理するシステム | TypeScript | 2025-06-20 | ✅ Active |
| [subsidy-task-admin](https://github.com/spot-s-system/subsidy-task-admin) | 助成金の出力とタスク管理を行うシステム | TypeScript | 2025-06-10 | ✅ Active |
| [spot-s-user](https://github.com/spot-s-system/spot-s-user) | 手続き申し込み用ユーザー管理システム | TypeScript | 2025-06-11 | ✅ Active |

### 🪽 freeeアプリ

| リポジトリ | 説明 | 言語 | 最終更新 | ステータス |
|-----------|------|------|----------|------------|
| [salary-diff-detector](https://github.com/spot-s-system/salary-diff-detector) | freeeAPIからの情報をもとに給与差分を表示する | TypeScript | 2025-06-20 | ✅ Active |
| [freee-office](https://github.com/spot-s-system/freee-office) | freeeの従業員情報をオフィスステーション向けに変換するFreeeアプリ | TypeScript | 2025-06-19 | ✅ Active |

### 🔧 ブラウザ拡張

| リポジトリ | 説明 | 言語 | 最終更新 | ステータス |
|-----------|------|------|----------|------------|
| [chrome-freee-extension](https://github.com/spot-s-system/chrome-freee-extension) | freee人事労務の画面に賃金台帳と出勤簿を表示するGoogle拡張 | TypeScript | 2025-05-27 | ✅ Active |

## 📈 統計

- **総リポジトリ数**: 9

## 🎯 プロジェクトの特徴

1. **freee連携**: 4つのプロジェクトがfreee APIと連携
2. **自動化重視**: OfficeStation、Stripe、メール送信などの自動化
3. **クラウドネイティブ**: Google Cloud、Chrome拡張など

## 🛠️ 技術スタック

- **言語**: TypeScript (主要)
- **プラットフォーム**: Google Cloud Platform, Chrome Extensions
- **API連携**: freee API, Stripe API, Google Drive API
- **自動化**: Cloud Functions, Cloud Run Jobs

## 📝 メンテナンス推奨事項

1. Sentryの追加

2. テストファイルの追加

3. 権限の明確化

4. セキュリティルールの設定
