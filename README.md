## Alpine, docker-in-docker, corretto JDK, sbt

docker image created to be used in CI/CD

### Components used:

1. Base layer: alpine3.14, docker-in-docker
2. Add temurin jdk 21  https://github.com/adoptium/containers/blob/f6d4923380ecb1ec4b0d58c633ebb0aeed4c8332/21/jdk/alpine
3. Add sbt https://github.com/eed3si9n/docker-sbt/blob/master/jdk11/alpine/Dockerfile
