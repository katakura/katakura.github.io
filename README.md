# katakura.github.io

Jekyllで構築したポートフォリオサイト。GitHub Pagesで公開する。

## ローカルプレビュー

```bash
bundle install
bundle exec jekyll serve
```

`http://localhost:4000` で確認できる。

## コンテンツの更新

- `_data/profile.yml`: 名前・肩書き・自己紹介・連絡先
- `_data/skills.yml`: スキル一覧
- `_data/experience.yml`: 職歴
- `_data/projects.yml`: プロジェクト一覧

## デプロイ

`katakura/katakura.github.io` という名前でGitHubリポジトリを作成し、`main`ブランチにpushすると
GitHub Pagesが自動的にビルド・公開する。
