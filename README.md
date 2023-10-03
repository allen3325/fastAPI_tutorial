# 資料庫啟動方法
---
### In docker-compose.yml.example
1. 複製一份，並取名為 docker-compose.yml
2. 將 **POSTGRES_USER**, **POSTGRES_PASSWORD**, **PGADMIN_DEFAULT_EMAIL**, **PGADMIN_DEFAULT_PASSWORD** 改成自己的資訊

### 啟動資料庫以及 pgAdmin
在目錄底下執行命令：
```bash
# 啟動資料庫以及 pgAdmin
docker compose up
```


