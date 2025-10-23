
# N8N

## Links
- https://n8n.io/
- https://github.com/n8n-io/n8n
- https://hub.docker.com/r/n8nio/n8n

## Hướng dẫn
- https://docs.n8n.io/
- https://github.com/n8n-io/n8n-docs

  
## Cài đặt Selfhost

### với nodejs - tạo dự án tai máy
- Cài nodejs https://nodejs.org/en/

Chạy lệnh cài n8n  
```
npx n8n
```

### hoặc với Docker 
- cài Docker

Chạy lệnh docker thiết lập n8n  
```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

### cài n8n có sẵn llm
- https://github.com/n8n-io/self-hosted-ai-starter-kit

