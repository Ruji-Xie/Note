- keep a container running

```bash
docker run -d centos tail -f /dev/null
```

- shell into a container as root

```bash
docker exec -it <containner-names> bash
```
-it: interacitve mode
