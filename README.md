# Docker Java Build and Run (Multi stage)
A starter dockerfile template to  build and run a java application using  multistage builds.

https://docs.docker.com/develop/develop-images/multistage-build/#use-multi-stage-builds

The Dockerfile uses a maven image to build the application , and a very lean image based on alpine to run the java application.

This is a just a starter template for now without any frills; intended to be forked for your own use cases.

The hello-world project inside the app directory is based on https://github.com/pdurbin/maven-hello-world
