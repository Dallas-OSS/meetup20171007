# Dockerfiles

These docker files show how to build images with additional items like different files and confguration on top of the base image

Once you have built a docker container,  you want to save it in a registry like hub.docker.com.

``` docker build -t bobbymac/smokeping .```
``` docker tag <name> bobbymac/smokeping:lastest ```

``` docker push bobbymac/smokeping:lastest ```
