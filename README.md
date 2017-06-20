## sandbox-java

A docker container based on alpine (openjdk:alpinee) for running java exercises in sandbox.

It includes:

* openjdk, JUnit
* sandbox worker

## Working with this container

Build
`docker build -t mariosky/sandbox-java sandbox-java/`

Run Interactively
`docker run -t -i mariosky/sandbox-java /bin/sh`
