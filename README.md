## 環境設定
```shell
cp .env.example .env
```
.env内、**ELASTICSEARCH_HOSTS**のパラメータを設定（設置先のドメイン名）
## 起動  
```shell
$ cd ./
$ docker compose up -d 
```

## 停止
```
docker compose down
```

## エンドポイント
elasticsearch http://ドメイン名:9200  
kibana http://ドメイン名:5601