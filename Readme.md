# Sample ASP.NET Core Docker Application

## Build
```
docker build --rm --pull -f "./Dockerfile"  -t "sample:latest"
```

## Run
Starts the container. Should be available under ``localhost:5000``
```
docker run --rm -d  -p 5000:5000/tcp sample:latest 
```