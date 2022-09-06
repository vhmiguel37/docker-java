## docker-multi-stage-build-demo

To build the image: 

```shell
$ cd docker-multi-stage-build-demo
$ docker build -t java-app/docker-multi-stage-build-demo .
```

## docker-normal-build-demo

To build the image:

```shell
$ cd docker-normal-build-demo
$ docker build -t java-app/docker-normal-build-demo .
```

## docker-package-only-build-demo

First, package the source code:

```shell
$ cd docker-package-only-build-demo
$ mvn clean package
```

Then, build the image:
```shell
$ docker build -t java-app/docker-normal-build-demo .
```
