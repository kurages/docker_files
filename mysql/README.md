# mysql
## 起動
```bash
$ docker compose up
```

## ポート変更
```bash
$ cat example.env
PORT=3307

$ docker compose --env-file=example.env up
```


