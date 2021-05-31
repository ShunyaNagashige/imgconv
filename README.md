# 画像形式変換コマンド
指定ディレクトリ以下の画像ファイルを変換します。2021/2頃に作成．

## 使用言語，環境，テクノロジー
- Go
- Git,Github
- Docker,Docker Compose

## 使用方法
$ docker-compose up --build
を実行して環境構築を行う．

次に，imgconvディレクトリに移動して、以下のコマンドを実行する。

`./imgconv -s jpg -d -png [ディレクトリ]`

もしくは、

`go run main.go -s jpg -d png [ディレクトリ]`

## オプション
* `-s` 変換対象画像の形式(デフォルト：jpg)
* `-d` 変換後の画像の形式(デフォルト：png)

## 注意
docker + vscode の環境にて開発しているため、golandを使用している方は一部不都合等あるかもしれません。ご指摘いただければ可能な限り対応します。