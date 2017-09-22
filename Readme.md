# 開発周辺一式

今プロジェクトでは以下のアプリケーション一式がDockerによって管理されています

- Jenkins
- Redmine
- Gitlab

## 各種手順書はこちらを参照

- [Jenkins](./doc/jenkins.md)
- [Gitlab](./doc/gitlab.md)
- [Redmine](./doc/redmine.md)

# 起動方法

```
> docker-compose up -d
```

# 稼働中のコンテナにログインする

「xxx」はコンテナID（先頭3桁）/ コンテナ名

```
> docker exec -it xxx /bin/bash
```