# docker-quagga-git

The Docker image for Quagga(http://www.nongnu.org/quagga/) from Git source

## Docker Pull Command

Download from [Docker Hub](https://hub.docker.com/)

`$ docker pull iwaseyusuke/quagga-git`

## Docker Run Command

```
$ docker run -it --rm --privileged iwaseyusuke/quagga-git
```

## Docker Compose

If you have installed [Docker Compose](https://docs.docker.com/compose/),
you can run container with:

```
$ wget https://github.com/iwaseyusuke/docker-quagga-git/raw/master/docker-compose.yml

$ docker-compose run --rm quagga-git
