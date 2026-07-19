# hrkz777.github.io

[Hextra](https://github.com/imfing/hextra) を使った Hugo サイトです。

## ローカルプレビュー

Hugo Extended 0.146.0 以上をインストールしてから実行します。

```sh
git submodule update --init
hugo server --buildDrafts --disableFastRender
```

サイトは `http://localhost:1313/` で確認できます。

## デプロイ

`main` ブランチへ push すると、GitHub Actions がサイトをビルドして GitHub Pages へデプロイします。
