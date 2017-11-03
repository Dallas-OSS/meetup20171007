# Dockerfiles

These docker files show how to build images with additional items like different files and confguration on top of the base image

Once you have built a docker container,  you want to save it in registry like hub.docker.com.

1. Log in via the command line

``` docker login ```
2. Build..then tag...then push

``` docker build -t bobbymac/smokeping .```

``` docker tag <name> bobbymac/smokeping:lastest ```

``` docker push bobbymac/smokeping:latest ```
