# DNS
docker run --name dns --restart always --dns 8.8.8.8  -v /var/run/docker.sock:/docker.sock phensley/docker-dns
