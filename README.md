# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
##### リモートリポジトリとは、インターネット上あるいはその他ネットワーク上のどこかに存在するプロジェクトのこと。
##### ローカルリポジトリとは、開発者の手元のパソコンにあるリポジトリのことをいう。

## プッシュとマージの違いは何でしょうか？
##### プッシュとは、ローカルリポジトリにコミットした変更をリモートリポジトリにアップロードすることです。プッシュを行うと、自分がファイルに加えた変更が他の作業者にも公開されます。
### マージは、Gitにおいて分岐した履歴を戻して統合する手段です。

## コミットとプッシュの違い
##### コミットとは、ローカルで編集したファイルや追加したファイルをGit（ローカルリポジトリ）に登録すること。
##### プッシュとは、ローカルリポジトリにコミットした変更をリモートリポジトリにアップロードすることです。プッシュを行うと、自分がファイルに加えた変更が他の作業者にも公開されます。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
##### 変更履歴をあとからみたときに、どのような変更を行ったのかをすばやく認識できるようシンプルかつ分かりやすく書く。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
##### プルリクエストでマージするフローだと第三者からのコードレビューができる為、事前にバグを発見することが可能。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
##### 先にマージされた変更内容を取り込む。後にマージしようとしている変更内容を取り込む。どちらの変更内容も取り込む