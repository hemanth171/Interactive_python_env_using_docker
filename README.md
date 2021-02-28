# Interactive python environment using docker

## Command to build docker container
```
docker build -t mytestproj .
```

## Command to run interactive python environment
```
docker run --rm -it -v $pwd:/home mytestproj
```