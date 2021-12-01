## Alpine, docker-in-docker, corretto JDK, sbt

docker image created to be used in CI/CD

### Components used:

1. Base layer: alpine3.14, docker-in-docker
2. Add Corretto layer for alpine 3.14: https://github.com/corretto/corretto-docker/blob/main/11/jdk/alpine/3.14/Dockerfile
3. Add sbt https://github.com/eed3si9n/docker-sbt/blob/master/jdk11/alpine/Dockerfile


### Notes

It's best to use SBT 1.5.5, Scala 2.13.7 or rebuild with desired versions if needed
