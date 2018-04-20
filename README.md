# docker-ruby-builder
Node/Npm image with some additional build dependencies, that are needed to build some node modules.

The additional build dependancies in this image are:

- python
- make
- linux-headers
- libstdc++
- libgcc
- gcc
- g++
- native-deps
- some node packages like protractor, mocha, code climate reporter etc

## Usage

    docker run amaysim/node-builder:9-alpine-1.4.0 node --version
    docker run amaysim/node-builder:8-alpine npm --version