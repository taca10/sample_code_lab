author: taca
summary: はじめて学ぶRuby on Rails開発入門
id: codelab-rails-markdown
categories: codelab,Ruby,RubyonRails
environments: Web
status: Published
feedback link: https://github.com/ree-rishun/codelab-zenn
analytics account:


# Ruby on Rails入門

## Ruby on Rails入門 - はじめてのRuby on Railsチュートリアル
Duration: 0:1500

### 環境構築
#### Paize Cloud使います。
ブラウザ上で開発環境を構築することができます。
ただし、無料版の場合は作った環境は1日で消えてしまいます。

[PaizaCloudのサイトはこちらです。](https://paiza.cloud/ja/)

メールアドレスやパスワードを設定して、アカウント作成お願いします。
### サーバを作る
「新規サーバー作成」をクリック

サーバー名は適当につけてもらっても大丈夫です。
とりあえず contact-sample-app とします。

Ruby on Rails、phpMyAdmin、MySQLを選んでから、もう一度「サーバを作る」を押します。

### Railsアプリケーション作成

左側のターミナルを押してください！
ターミナル(黒い画面)が起動したら下記のコマンドを入力してください。
```
rails new contact-sample-app --database=mysql
```

### データベース作成

```
cd contact-sample-app
bundle install
rails db:create
```

データベースが作成できました。

Rubu on Rails 起動コマンド

```
rails s
```

画面の左側に地球マークと3000と書かれたボタンがでます。
クリックすると、ページが表示されます。

