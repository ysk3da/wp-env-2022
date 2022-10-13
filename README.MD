# wp-env

wp-envを使うにはdockerが必要です。
まずはdockerをインストールしてください。

## Dockerのインストール

[docker](https://www.docker.com/)


次にwp-envをインストールします。
本テンプレートではすでにpackage.jsonに記述されていますので、

```shell
npm i
```

にて各nodeモジュールをインストールしてください。

## install

```shell
npm i -D @wordpress/env
```

## WordPressを起動する

```shell
npx wp-env start
```

http://localhost:8888/

http://localhost:8888/wp-login.php

ログインユーザー・パスワードは admin / password