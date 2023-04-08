# dockerイメージ作成
```
cd ansible
docker build -t ansible-training:1 .
```

# dockerイメージ確認
```
docker images
```

# dockerコンテナ作成＆起動
```
docker run -it -d --name ansible-training ansible-training:1
```

# dockerコンテナログイン
```
docker container exec -it ansible-training bash
```

# dockerコンテナ確認
```
docker ps -a
```

# dockerコンテナ起動
```
docker start ansible-training
```

# dockerコンテナ停止
```
docker stop ansible-training
```

# dockerコンテナ削除
```
docker rm ansible-training
```

# dockerイメージ削除
```
docker rmi ansible-training:1
```

# ansibleハンズオンサイト（Qiita）
https://qiita.com/Shoma0210/items/7d7d24d7c3f95f19b427