# segurvita.github.io
これは https://segurvita.github.io/ の原稿を管理するリポジトリです。



## 利用技術

- [Hugo](https://gohugo.io/)
- [Academic theme](https://sourcethemes.com/academic/)



# Usage

## 開発ツール導入

Hugo Extended v0.122.0 をインストールしてください。

実行ファイルは以下から入手できます。

https://github.com/gohugoio/hugo/releases/tag/v0.122.0

Homebrewだと、0.122.0をインストールできないようなので、ご注意ください。

Chocolateyなら、以下のコマンドでインストールできます。

```bash
choco install hugo-extended --version=0.122.0
```



## 開発環境構築

以下のコマンドでソースコードをダウンロードします。本プロジェクトには、Gitサブモジュールが含まれるので、再帰的にダウンロードします。

```bash
git clone --recursive https://github.com/segurvita/segurvita.github.io.git
```

もし `recursive` をつけ忘れてクローンしてしまった場合は、以下のコマンドを実行してください。

```bash
git submodule update --init --recursive
```



## プレビュー

以下のコマンドでサーバーを起動します。

```bash
hugo server
```

ブラウザで http://localhost:1313 にアクセスすれば、プレビューできます。



## デプロイ

`master` ブランチはGitHub Page公開用であり、開発用途では利用しません。開発用途では、デフォルトブランチ `source` を利用します。

GitHub Actionsにより、 `source` ブランチを更新すれば、自動でデプロイされます。



## 参考

- [【初心者向け】Hugo + GitHub Pagesで静的なポートフォリオを作る](https://qiita.com/nkjzm/items/ab8595f185348de7ba7e)

