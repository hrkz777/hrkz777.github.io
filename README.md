# hrkz777.github.io

HugoとVS Code Front Matterで管理する個人メモサイトです。

## Preview

Hugoをインストールした後、VS Codeで`Terminal: Run Task`から`Hugo: Preview`を実行します。Front Matterのプレビューは`http://localhost:1313`を使用します。

```powershell
winget install Hugo.Hugo.Extended
hugo server -D
```

## Create an article

Front Matterダッシュボードで`Article`を選び、`content/posts/<slug>/index.md`として作成します。slugと画像を含むファイル名には、英小文字、数字、ハイフンだけを使用してください。記事の画像は`index.md`と同じフォルダへ配置します。

## Deployment

`main`へのpushでGitHub Actionsがサイトをビルドします。GitHubリポジトリの`Settings > Pages > Build and deployment > Source`は`GitHub Actions`に設定してください。
