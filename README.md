# graphdb-free-docker
Docker image for GraphDB free

Usage:
- download the respective GraphDB Free ZIP from https://graphdb.ontotext.com/ and place it to the root of this project
- build the image using `docker build . --build-arg GRAPHDB_ZIP=<PATH_TO_GRAPHDB_ZIP_FILE> -t graphdb-free`
- run the container as `docker run -p 7200:7200 graphdb-free`