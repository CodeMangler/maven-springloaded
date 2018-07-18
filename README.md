# Maven Springloaded

This is a docker image containing `maven` repository metadata for Spring and a couple of other dependencies. Saves on the time taken by `maven` to download metadata (`pom`s) in a `maven` image.

Meant to be used as base image of the build stage in a [multistage docker build](https://docs.docker.com/develop/develop-images/multistage-build/) file for building Spring/Spring Boot application docker images.
