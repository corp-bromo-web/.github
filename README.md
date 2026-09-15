# .github

corp-bromo-web の共通テンプレート置き場です。

このリポジトリに置いたファイルは、GitHub の
[default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
の仕組みによって、**corp-bromo-web 配下の全リポジトリへ自動的に配られます**（private リポジトリを含む）。
各リポジトリへコピーする必要はありません。

## 置いてあるもの

| ファイル | 内容 |
| --- | --- |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | PR の共通テンプレート |
| [`.github/pr-review-guide.md`](.github/pr-review-guide.md) | 各欄の意味と判断基準 |
| [`.github/markdown-guide.md`](.github/markdown-guide.md) | PR 本文の Markdown の書き方 |
| [`.github/repo-checks.example.md`](.github/repo-checks.example.md) | 案件固有の確認項目のサンプル |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | Issue の共通テンプレート |

## 案件リポジトリ側に置くもの

案件ごとに内容が変わるものは、各リポジトリに置きます。

| ファイル | 内容 |
| --- | --- |
| `.github/repo-checks.md` | そのリポジトリ固有の確認項目（ブレークポイント、ビルドの要否など） |
| `docs/local-setup.md` | そのリポジトリのローカル環境セットアップ手順 |

## 編集するときの注意

- **リポジトリ側に同名のファイルがあると、そちらが優先され、共通版は無視されます。**
  部分的なマージはされません
- **このリポジトリは public です。**
  個人名・アカウント名・案件固有の情報は書かないでください
