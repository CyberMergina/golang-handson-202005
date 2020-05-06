# Step 02
「Hello, World」を表示するエンドポイントを持ったコードをGAE/Go上で動かす

## Google Cloud SDKのセットアップ
```
$ cd ~
$ wget https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-280.0.0-linux-x86_64.tar.gz
$ sudo tar xvzf google-cloud-sdk-280.0.0-linux-x86_64.tar.gz
$ cd google-cloud-sdk/
$ ./install.sh
$ ./bin/gcloud init
$ exec $SHELL -l
$ gcloud version
$ gcloud components update
$ gcloud projects describe [プロジェクト名]
$ gcloud app create --project=[プロジェクト名]
$ gcloud components install app-engine-go
```

# アプリケーションのデプロイ
```
$ gcloud app deploy
$ gcloud app browse
```

ブラウザから「gcloud app browse」で返るアドレスにアクセスすると「Hello world」が表示される
