# Lumen (5.4.4)
laravel製軽量フレームワーク Lumen を使ってみる。

※ Laravel Components 5.4.*

## 必要条件

* PHP >= 5.6.4
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension

## Lumenをインストールする

GitHubからコードをクローンし、composerを使ってLumen本体を配置します。

※ vendorフォルダ内にインストールされます。

**開発環境の場合)**
```
$ git clone https://github.com/reflet/app-lumen5.4.git .
$ composer create-project
```
※ 環境設定ファイル「.env」が自動作成されます。

**本番環境の場合**
```
$ git clone https://github.com/reflet/app-lumen5.4.git .
$ composer install
```

