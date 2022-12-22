# 最初の第一歩(ソースコードがない、一番初めに行う)
1. dockerディレクトリに移動する
1. 以下のコマンドを実行する
    1. `mkdir react`
    1. `cp ./compose/create_react/compose.yml ./`
    1. `chmod +x ./create_react.sh`
    1. `docker compose build`
    1. `docker compose run --rm react`

# reactの開発環境の実行
1. dockerディレクトリに移動する
1. 以下のコマンドを実行する
    1. `chmod +x dev_react.sh`
    1. `cp ./compose/dev_react/compose.yml ./`
    1. `docker compose build`
    1. `docker compose up`

# reactのビルド
1. dockerディレクトリに移動する
1. 以下のコマンドを実行する
    1. `chmod +x build_react.sh`
    1. `cp ./compose/build_react/compose.yml ./`
    1. `docker compose build`
    1. `docker compose up`