git のコマンド練習用フォルダ

- 既存のフォルダを github にアップする場合

1. github で新規レポジトリを作成
2. git init
3. git config --global user.name "任意の名前"
4. git config --global user.email "任意のアドレス"
5. git add .
6. git commit -m "ここにコメント"
7. git branch -M master ##コミット先のブランチを master という名前に指定
8. git remote add origin git@〜 ## git@〜」の箇所にアップロード先の github のリンクを入力します
9. git push -u origin main

git clone
git add
git commmit
git push
git pull
