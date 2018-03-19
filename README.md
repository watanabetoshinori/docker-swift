# docker-swift 2.2

### An Ubuntu 14.04 Docker image for [Swift 2.2](https://swift.org).

### Docker Instructions

##### Pull the Docker Image From Github:

```bash
git clone https://github.com/watanabetoshinori/docker-swift
cd docker-swift
docker build -t swift:2.2-dev .
```

##### Create a Container from the Image and Attach It:

```bash
docker run --privileged -it --name swift2 swift:2.2-dev /bin/bash
```

##### To Start and Attach Your Image Later:

Start your image with name `swift2`

```bash
docker start swift2
```

and then attach it

```bash
docker attach swift2
```
