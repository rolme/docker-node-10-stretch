```sh
docker build -t rolme/node-10-stretch .
docker run -it --rm rolme/node-10-stretch
docker login && docker push rolme/node-10-stretch
```