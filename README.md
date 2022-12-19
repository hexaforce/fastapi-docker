```
docker build . -t hexaforce/fastapi-docker
docker run -it -p 80:80 hexaforce/fastapi-docker
```

```
docker login
docker push hexaforce/fastapi-docker
```