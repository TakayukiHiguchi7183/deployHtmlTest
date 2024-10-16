# deployHtmlTest

## 概要

* 目的：Azure環境へのデプロイやCICD実装の練習用アプリケーション
* 言語：htmlファイル。今後拡張予定
* 環境へのアクセス
  * 開発環境　[URL](https://delightful-bay-0ed4f1700.5.azurestaticapps.net/)
  * 本番環境　[URL](https://azuredeploytest001.azurewebsites.net/)

## インストール方法（installation）

1. リポジトリをクローンします:
   ```bash
   git clone https://github.com/TakayukiHiguchi7183/deployHtmlTest.git
2. 実行します
3. この辺は随時埋める

## 実行方法（usage）

1. プロジェクトをローカル環境で動かすには、以下のコマンドを実行します
   ```bash
   npm start
2. localhost:3000にアクセスしてください

## 設定方法（Configuration）

1. 今の所なし

## 貢献方法（Contributing）
プルリクエストやバグ報告は歓迎です！以下の手順で貢献できます

1. フォークしてください。
2. 新しいブランチを作成します: `git checkout -b feature-branch`
3. コードをコミットします: `git commit -m 'Add new feature'`
4. プルリクエストを送ってください。

## テスト方法(Testing)

1. 今の所なし

## デプロイ(Deploying)
・Actionsによるステージングへの自動実行を行い、Azureコンソール上でproduct環境へスワップします

1. develop環境へデプロイすると、devDeployフローにより開発環境（[URL](https://delightful-bay-0ed4f1700.5.azurestaticapps.net/)）にデプロイ
2. 動作確認し、本番移送しても問題なければdevelopブランチをmainブランチにマージ（プルリクエスト）
3. deployフローで本番環境（[URL](https://azuredeploytest001.azurewebsites.net/)）にデプロイ

## 利用ライセンス

1. 今の所なし

