# Workflow Sample

このリポジトリは個人的なサンプルworkflowです。
今正しく動いているworkflowは以下

- release_drafter.yml
  - Pull Request作成時に自動でラベリング
  - ラベルに基づいてリリースノートを自動作成
- release_triggered_deployment.yml
  - リリースをpublishしたときにデプロイ前のチェックとデプロイをして、結果をDiscordへ通知
- auto_merge.yml
  - release_drafter.ymlのmasterブランチ以外での実行完了でトリガ
  - 実行内容については未実装
