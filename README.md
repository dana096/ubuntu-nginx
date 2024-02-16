# ubuntu-nginx

### 1. hub 에서 ubuntu pull & run
```
$ sudo docker pull ubuntu:22.04
[sudo] password for dana096:
22.04: Pulling from library/ubuntu
01007420e9b0: Pull complete
Digest: sha256:b6ec12b8345cdc0714add139b17803301aec077509820faf970a1dab0a7fce78
Status: Downloaded newer image for ubuntu:22.04
docker.io/library/ubuntu:22.04

$ sudo docker run -it --name ubuntu-nginx ubuntu:22.04
```

### 2. nginx 설치
```
root@b0b2267cfe02:/# apt update
root@b0b2267cfe02:/# apt install nginx
```
