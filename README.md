Live site: https://nhpoj.ddns.net:8888

### Cài đặt trên máy Linux

1. Cài đặt môi trường

    ```bash
    sudo apt-get update && sudo apt-get install -y vim python-pip curl git
    pip install docker-compose
    ```

2. Cài Docker 

   ```bash
   sudo curl -sSL get.docker.com | sh
   ```

3. Restore db
   Thư mục chuyển vào usr/local/bin để restore db 
   ```bash
   psql -f /root/db_backup_xxxxxxx.sql -U onlinejudge
   ```

Tài liệu: http://opensource.qduoj.com/
