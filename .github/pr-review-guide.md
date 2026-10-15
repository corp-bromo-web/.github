# PR テンプレートの使い方

PRとIssueの書き方、PRの確認の進め方は、ナレッジサイトにあります。

- PRを出す：https://knowledge-hub.corp-bromo.com/git-pr-write
- PRをレビューする：https://knowledge-hub.corp-bromo.com/git-pr-review
- Issue を立てる：https://knowledge-hub.corp-bromo.com/git-pr-review-issue
- 案件ページ：https://knowledge-hub.corp-bromo.com/projects

ナレッジサイトは社内向けで、Basic 認証がかかっています。

## このテンプレートの配られ方

このリポジトリは GitHub の
[default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
の仕組みを使っています。
**corp-bromo-web 配下のリポジトリは、自分で持っていないファイルをここから自動的に受け取ります。**
各リポジトリにコピーする必要はありません。

そのため、次の点に注意してください。

- **リポジトリ側に `.github/pull_request_template.md` を置くと、組織共通版は完全に無視されます。**
  一部だけ差し替えることはできません。案件固有の確認項目は、ナレッジサイトの案件ページに書きます
- **このリポジトリは public です。** 個人名・アカウント名・案件固有の情報は書かないでください

Issue テンプレート（`.github/ISSUE_TEMPLATE/` の中のファイル。レビュー中の気づきを書く `review-finding.md` を含む）も、同じ仕組みで配られます。
