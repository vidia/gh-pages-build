# Dockerfile for building Github Pages Jekyll sites

Simple dockerfile to build a jekyll site into static files for deployment.

After building, run this file using the following: 

````
docker run -t --rm -v "$PWD":/usr/src/app <name of this image>
````
