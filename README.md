.git ディレクトリに保存される

objectsの中にオブジェクトが保存される

# ファイルごと削除
git rm <ファイル名>
git rm -r <ディレクトリ名>

# ファイルを残したいとき
git rm --cached <ファイル名>

# ファイルの移動
git mv <旧ファイル> <新ファイル>

# リポジトリから変更を取り消す
git restore --staged <ファイル名>

# ステージから取り出す場合
git restore <ファイル名>

# コミットの変更
git commit --amend

## 直前のコミットメッセージを使う場合
git commit --amend --no-edit
