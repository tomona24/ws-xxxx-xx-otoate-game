
## 使用パッケージ

- express
- mongoose


##  Mongo DBのインストール

本課題ではMongo DBを使って課題を進めるのでMongoのインストールが必要です。

- mongodbのインストール

```console
$ brew tap mongodb/brew
$ brew install mongodb-community@4.4
```

- mongodb の起動（サービスへの登録）

```console
$ brew services start mongodb-community 
```
- mongodbへの接続

その他操作は下記記事参照ください。

[MongoDB 超入門](https://qiita.com/saba1024/items/f2ad56f2a3ba7aaf8521_)


## 補足記事

- [mongoose | 公式](https://mongoosejs.com/docs/index.html)
- [Node.js用MongoDBライブラリ mongooseの基本操作まとめ（すぐ試せるサンプル付き）](https://qiita.com/takehilo/items/4b89f8ee432b0a06c691)
- [node.js + expressでPOSTを受け取る & POSTパラメータをJSONで取得する](https://qiita.com/ktanaka117/items/596febd96a63ae1431f8)
