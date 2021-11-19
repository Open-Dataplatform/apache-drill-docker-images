# apache-drill-docker-images
This repo will serve as a place to house our custom apache drill images.

In the current setup these will probably be a copy of [Agirish docker images](https://github.com/Agirish/drill-helm-charts/tree/master/dockerfiles)

With some minor changes to the files build into the image.

# Agirish's readme
## Building Docker Images
The dockerfiles directory contains everything required to build and customize Docker images for Apache Drill and Apache ZooKeeper.

Docker images are available on [Docker Hub](https://hub.docker.com/u/agirish/).

### Build ZooKeeper
Takes in 1 parameters: project version

Example:
```
cd dockerfiles/zookeeper
./build.sh 3.6.0
```

### Build Drill
Takes in 1 parameters: project version

Example:
```
cd dockerfiles/drill
./build.sh 1.17.0
```