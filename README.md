# Docker examples

This is a repository of Docker example code that I used in a talk at [Proxama](http://proxama.com/) as an introduction to Docker.

## Contents

### Example 1

The first example is a single, simple docker build that creates an image to run a "Hello, world" python script.

How to run:

    cd example1
    docker build -t docker_example_1 ./
    docker run docker_example_1

### Example 2

The second example is a pair of docker builds:

* A simple web server that serves up a single file, hello.txt

* A service that makes a web request to the server and outputs the result

This example also contains a docker-compose file which can be used for running the pair of images as a single unit.

How to run:

    cd example2
    docker-compose up
