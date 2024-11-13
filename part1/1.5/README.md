```bash
rellen@lx1-fuxi119:~$ docker image ls
REPOSITORY                              TAG                IMAGE ID       CREATED         SIZE
devopsdockeruh/simple-web-service       ubuntu             4e3362e907d5   3 years ago     83MB
devopsdockeruh/simple-web-service       alpine             fd312adc88e0   3 years ago     15.7MB

```

```bash
rellen@lx1-fuxi119:~$ docker exec -it 1.5 sh
/usr/src/app # tail -f ./text.log
2024-09-09 15:09:23 +0000 UTC
2024-09-09 15:09:25 +0000 UTC
2024-09-09 15:09:27 +0000 UTC
2024-09-09 15:09:29 +0000 UTC
2024-09-09 15:09:31 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
2024-09-09 15:09:33 +0000 UTC
2024-09-09 15:09:35 +0000 UTC
2024-09-09 15:09:37 +0000 UTC
2024-09-09 15:09:39 +0000 UTC
2024-09-09 15:09:41 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```
