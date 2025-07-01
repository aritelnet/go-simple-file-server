# go-simple-file-server
シンプルなGo製の静的ファイルサーバーです。
A very simple directory hosting web server.

## 概要

- カレントディレクトリ配下の `htdocs` フォルダを公開します  
- もし `htdocs` がなければ起動時に自動作成されます  
- ポート番号は固定で `8080`  
- 依存はGo標準ライブラリのみで超軽量・高速です  


## ビルド方法

### ローカル環境でビルド（Go 1.24 以降）

```bash
go build -o file-server main.go
````


## 実行方法

`htdocs` フォルダを用意（なければ自動作成されます）

```bash
./file-server
```

ブラウザで以下にアクセスしてください：

```
http://localhost:8080/
```


## GitHub Actions による自動ビルド

* Windows, Linux (amd64/arm64), macOS (amd64/arm64) 向けバイナリを自動生成
* タグをつけて push すると Workflow が走ります


## ライセンス

MIT License

