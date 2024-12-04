# プロジェクトの概要
# 改めてgithubの学習

ローカルリポジトリを初期化する	git init

ローカルリポジトリへ記録する	git　add .

リポジトリで変更されたファイルを確認	git status

git　commit -m "コミットメッセージ"

ローカルリポジトリの状態を確認		git diff

ローカルリポジトリの履歴を確認		git log　

ローカルリポジトリの変更を元に戻す	git restore <ファイル名>

ブランチ作成と移動　 git checkout -b feature-branch

ファイル作成    touch ファイル名

# 大体プルリクエスト送るまでの手順
ローカルリポジトリへ記録する	git　add .

git　commit -m "コミットメッセージ"

git push

# mainブランチにマージしてプッシュ
違うブランチにいる場合
git checkout main

git merge マージしたいブランチ名

git push origin main

強制プッシュ
git push origin プッシュしたいブランチ:main



# スマプロハッカソンで作成したプログラム
main.py
chatgpt.py
googlemap_api.py
request.py
response.py
description.py
place.py