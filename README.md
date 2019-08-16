# Overview

CushionDocker includes the `docker-compose.yml` file that is used to build and run the [CushionServer](https://github.com/CushionDB/CushionServer) and [CushionCouch](https://github.com/CushionDB/CushionCouchDocker) containers. These two containers make up the backend of CushionDB and are designed to work with [CushionClient](https://github.com/CushionDB/CushionClient).

## Usage

Rather than explicitely running the `docker-compose up` command, you should start by running the `cushion-backend-init` script. This will prompt you for information that will be used for various configurations for the containers.

<p align="center"><img src="https://cushiondb.github.io/img/cushion-backend-init.gif"></p>

Next, you can run the `cushion-backend-start` script which will make sure proper configurations have been setup, then will run `docker-compose up` for you.

<p align="center"><img src="https://cushiondb.github.io/img/cushion-backend-start.gif"></p>

# The Team

[Avshar Kirksall]() *Software Engineer* Brooklyn, NY

[Jaron Truman]() *Software Engineer* Las Vegas, NV

[Daniel Rote]() *Software Engineer* Seattle, WA
