## DNS container 
`docker run --name dns --restart always --dns 8.8.8.8 -v /var/run/docker.sock:/docker.sock -p 172.17.42.1:53:53/udp  phensley/docker-dns`
