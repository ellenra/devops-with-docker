```bash
rellen@lx1-fuxi119:~$ docker run -d -it --name 1.3 devopsdockeruh/simple-web-service:ubuntu


rellen@lx1-fuxi119:~$ docker exec -it 1.3 tail -f ./text.log
2024-09-08 13:53:04 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
2024-09-08 13:53:06 +0000 UTC
2024-09-08 13:53:08 +0000 UTC
2024-09-08 13:53:10 +0000 UTC
2024-09-08 13:53:12 +0000 UTC
2024-09-08 13:53:14 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```
