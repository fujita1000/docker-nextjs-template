## git cloneしてローカルに保存

## git remote -vでpush先確認

## git remote set-url origin [url] でpush先変更

## git remote -v で確認

# プロジェクトディレクトリ内にあるファイルやディレクトリを全てコミット 
$ git add .
$ git commit -m "Initial Commit"

# 先ほど作成したGitHubリポジトリのURLをコピー&ペーストして、リモートブランチとして設定
git remote add origin https://github.com/your-name/project-name.git

# ローカルのファイルをアップロード
git push -u origin main


## Docker起動
docker-compose up --build

or 

docker-compose up

## Dockerでyarn起動
$ docker-compose exec app yarn

## Dockerでyarn dev起動
$ docker-compose exec app yarn dev

これはDocker環境でnext.jsアプリを作成するひな型です。

環境に応じて色々カスタマイズしてください。
