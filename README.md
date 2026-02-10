# SleepBlockerPrivacyPolicy

SleepBlockerアプリのプライバシーポリシーを公開するリポジトリです。

## 公開サイト

このプライバシーポリシーは、GitHub Pagesで公開されています：
https://yuu123456.github.io/SleepBlockerPrivacyPolicy/

## ファイル構成

- `index.md` - プライバシーポリシー（日本語版）
- `privacy-policy-en.md` - プライバシーポリシー（英語版）
- `_config.yml` - Jekyll設定ファイル
- `.github/workflows/deploy.yml` - GitHub Actions自動デプロイ設定

## 自動デプロイ

mainブランチへの変更が自動的にGitHub Pagesにデプロイされます。GitHub Actionsワークフローが以下を実行します：

1. リポジトリのコードをチェックアウト
2. Jekyllでサイトをビルド
3. GitHub Pagesに自動デプロイ

## GitHub Pagesの初期設定

初回のみ、以下の設定が必要です：

1. GitHubリポジトリの Settings > Pages に移動
2. Source を "GitHub Actions" に設定
3. Save をクリック

以降、mainブランチへのプッシュやマージで自動的にデプロイされます。

## プライバシーポリシーの更新

プライバシーポリシーを更新する場合は、`index.md` または `privacy-policy-en.md` を編集し、最終更新日を変更してください。

## ライセンス

このプライバシーポリシーは、SleepBlockerアプリ専用です。