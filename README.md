# misskey-nginx-proxy

Misskeyをnginxでプロキシし、Let's EncryptでSSL化する。

- [misskey](https://github.com/MT224244/misskey)
- [misskey-backup](https://github.com/MT224244/misskey-backup)
- misskey-nginx-proxy

# 起動方法

1. `.env.example` をコピーして `.env` を作る
1. `docker-compose.yml.example` をコピーして `docker-compose.yml` を作る
1. 必要な情報を入れる(ほとんどの場合弄らなくていいかも)
1. `docker compose up -d`
