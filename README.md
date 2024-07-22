# これはなに？

[JBUG岡山 #6 なんでもアリのBacklogバーリ・トゥード](https://jbug.connpass.com/event/317489/) で発表した、Webhookで飛んでくるJSONを保存したものです。

## ファイルの解説

```
├─01_issue                    -> 課題に関するイベント
│      01_add.json            -> 課題の追加
│      02_update.json         -> 課題の更新
│      02_update_2.json       -> 課題の更新(サンプルのJSONだと足りない項目があったので生データ)
│      03_comment.json        -> 課題にコメント
│      04_delete.json         -> 課題の削除
│      05_bulk_update.json    -> 課題をまとめて更新
│      06_information.json    -> お知らせの追加
│      06_information_2.json  -> お知らせの追加(サンプルのJSONだと足りない項目があったので生データ)
│
├─02_wiki                     -> Wikiに関するイベント
│      01_add.json            -> Wikiの追加
│      02_update.json         -> Wikiの更新
│      03_delete.json         -> Wikiの削除
│
├─03_file                     -> 共有ファイルに関するイベント
│      01_add.json            -> ファイルの追加
│      02_update.json         -> ファイルの更新
│      03_delete.json         -> ファイルの削除
│
├─04_version                  -> バージョン管理に関するイベント
│      01_svn_commit.json     -> Subversionコミット
│      02_git_push.json       -> Gitプッシュ
│      03_git_repo.json       -> Gitリポジトリの作成
│
├─05_project                  -> プロジェクトに関するイベント
│      01_project_join.json   -> プロジェクトに参加
│      02_project_leave.json  -> プロジェクトから脱退
│      03_version_add.json    -> 発生バージョン/マイルストーンの追加
│      04_version_update.json -> 発生バージョン/マイルストーンの更新
│      05_version_delete.json -> 発生バージョン/マイルストーンの削除
│
└─06_pr                       -> プルリクエストに関するイベント
        01_pr_add.json        -> プルリクエストの追加
        02_pr_update.json     -> プルリクエストの更新
        03_pr_comment.json    -> プルリクエストにコメント
```
