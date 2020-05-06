# golang-handson-202005


## 環境変数
secret.yaml
|ポート番号|例|備考|
|--|--|--|
|PORT|8080|go runで起動するwebサーバでLISTENするポート番号(GAEでも使われるため、基本は8080)|
|GOOGLE_APPLICATION_CREDENTIALS|"/home/username/gcp/xxxxxxxxxxxx.json"|Dialogflow用のサービスアカウントの認証キー|
|CHANNEL_SECRET|xxxxxxxxxxxx|LINEのチャンネルシークレット（Basic Settingの下部に記載）|
|CHANNEL_TOKEN|xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx|LINEのチャンネルアクセストークン（Messasing APIの下部に記載）|

## GCコマンド

```
$ gcloud app deploy
$ gcloud app browse
$ gcloud app logs tail -s default
```
