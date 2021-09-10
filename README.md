# empty-nodejs

This docker file can use to build an empty node js application with port expose to 8080. 

# How to use
Run build command on the working directory

    docker build . -t <username>\expose-port-node

Once the docker image is build locally, simply run the following command

    docker run -d -t -v <host directory>:\usr\src\app  -p 8080:8080 <username>\expose-port-node
