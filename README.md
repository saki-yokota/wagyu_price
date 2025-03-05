# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

- リモートリポジトリとは、Githubなどネット上に配置して複数人で共有するためのリポジトリ。
- ローカルリポジトリとは、開発者一人一人が作業するために自分のPC上に配置するリポジトリ。

## プッシュとマージの違いは何でしょうか？

- プッシュは、ローカルリポジトリの変更をリモートリポジトリに反映させる操作。
- マージは、別のブランチの変更内容を取り込む操作。

## コミットとプッシュの違い

- コミットは、ローカルリポジトリに変更内容を保存する操作。
- プッシュは、そのコミットをリモートリポジトリに反映させる操作。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

- どのような編集を行なったのかがわかるように簡潔に記すのが最適。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

- ローカルでマージするフローは、開発者がローカル環境でブランチを統合し、その結果をプッシュする。
- プルリクエストでマージするフローは、リモートリポジトリ上でコードレビューを受けてからブランチを取り込む。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

- コンフリクトを起こしているソースコード取り込み、エディタなどを使用して修正する。その後、コンフリクト解決で行った作業ををadd、commitする。