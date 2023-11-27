# Docker Zerotier Planet


## Run
```shell
docker run -itd --restart=unless-stopped \
--name zerotier-planet \
-p 3443:3443 \
-p 8000:8000 \
-p 9993:9993 \
-p 9993:9993/udp \
liasica/zerotier-planet:latest
```

## Upgrade
TODO
