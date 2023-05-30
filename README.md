# google-cloud

## セットアップ

pyaudioを使うので portaudio をインストールする

```bash
$ brew install portaudio
```

Poetryをインストールする。

```bash
$ pip install poetry
```

依存ライブラリをインストールする。

```bash
$ poetry install
```


## 実行方法

Speech-To-Text APIの有効にして、サービスアカウントの認証情報を取得する。

https://cloud.google.com/text-to-speech/docs/before-you-begin?hl=ja



プログラムを実行する。

```bash
$ python gcloud/speech2text/main.py 
音声認識ちゃんとできるか試してみる
出来てるような気がする
終了
Exiting..

プロセスは終了コード 0 で終了しました
```
