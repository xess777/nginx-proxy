# nginx-proxy

Host multiple websites with HTTPS on a single server.

## Setup

```bash
cd /var/www
git clone https://github.com/xess777/nginx-proxy.git
docker network create nginx-proxy
docker-compose up -d
```

Now the reverse-proxy is running.
