I started the process with:

```bash
docker run -it --name 1.4 ubuntu sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'
```

Then from another terminal I installed curl:

```bash
rellen@lx1-fuxi119:~$ docker exec -it 1.4 bash
root@bef22f53a058:/# apt-get update
root@bef22f53a058:/# apt-get install curl


```
