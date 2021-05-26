# docker_nmp
### 檔案結構
├── docker-compose.yml : 多容器設定檔
├── files : 自建資料夾，用來存放 image 的
│   └── php
│       └── Dockerfile 自定義的 php-fpm image
├── log : 在 docker-compose.yml 中定義，用來存放日誌
│   ├── mysql
│   └── nginx
│       ├── access.log
│       └── error.log
├── site.conf : 在 docker-compose.yml 中定義，用來修改 nginx 的設定檔。



