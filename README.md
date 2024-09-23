# crowdmoove_devautomation

## 1. Overview
Crowd Mooveの顧客であるmirubuzz様のスクレイピング対応で、パターン①のコードを改修。

## 2. Revisions
- 全体的なコードを修正
- AWSのDynamoDBに今までメールを送信したユーザの一覧を格納し、対象ユーザ作成時に重複チェックを行う
- Slackの通知はAWS上でなぜか動かないので調査中