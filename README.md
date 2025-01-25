# GitHub の使い方
## リポジトリへのpush
```
git init # gitの初期化
git add ファイル名 #ファイル名を[.]とするとディレクトリ内にあるすべてのファイルを選択
git commit -m "コメント" #コミットメッセージの追加
git switch -c ブランチ名 # ブランチの変更
git remote add origin ssh-url
git push -u origin ブランチ名
```

## リモートリポジトリからpull
```
git clone ssh-url
```