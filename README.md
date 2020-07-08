# docker-compose-LAMP-simple

Tạo mô hình LAMP đơn giản sử dụng Docker Compose

## Hướng dẫn sử dụng

Đầu tiên, clone thư mục này về

```
git clone https://github.com/tri105/docker-compose-LAMP-simple.git

cd docker-compose-LAMP-simple
```

Cài đặt Docker và Docker Compose

- Trên Linux: https://github.com/tri105/docker-labs/tree/master/Install
- Trên Windows
- Trên MacOS

### Phần source code

Bỏ source code vào trong thư mục `htdocs`

### Chạy docker-compose

Sử dụng lệnh

```
docker-compose up -d
```

Để tắt server

```
docker-compose down
```

### Phần database

Truy cập `localhost:8080` để vào phpmyAdmin và import `.sql` vào!

Hoàn thành!