- keep a container running
```bash
docker run -d centos tail -f /dev/null
```

- shell into a container as root
-it: interacitve mode
```bash
docker exec -it <containner-names> bash
```

