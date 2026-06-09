# Postman Collections

Thư mục này chứa collection kiểm thử cho Lab 05.

- Collection: `FIT4110_lab05_docker_compose.postman_collection.json`
- Environment: `postman/environments/FIT4110_lab05_local.postman_environment.json`

Bạn có thể chạy kiểm thử bằng:

```bash
npm run test:compose
```

Collection kiểm tra các endpoint:
- `GET /health`
- `GET /health` cho AI service
- `POST /predict` cho AI service
- `POST /readings`
- `GET /readings/latest`
- `GET /readings/{{reading_id}}`