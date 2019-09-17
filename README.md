Rust勉強用
============

## 環境構築手順

Hello Worldを出すまで
git cloneしてできたrust-workディレクトリで実施

`$ docker-compose -f docker-compose.yml up -d`

`$ docker exec -it rust-work_rust_1 bash`

`# export USER=rustWorker`

`# cd /usr/src/myapp`

`# cargo new helloworld`

`# cd /usr/src/myapp/helloworld/src`

`# rustc main.rs`

`# cd ./main`