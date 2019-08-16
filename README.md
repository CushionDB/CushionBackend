# Overview

CushionDocker includes the `docker-compose.yml` file that is used to build and run the [CushionServer](https://github.com/CushionDB/CushionServer) and [CushionCouch](https://github.com/CushionDB/CushionCouchDocker) containers. These two containers make up the backend of CushionDB and are designed to work with [CushionClient](https://github.com/CushionDB/CushionClient).

## Usage

In the Repo run `./bin/cushion-beckend-start`. The first time this command it run it will prompt you for some information. Make sure that if you update any configuration you will need to update the cushionClient configuration as well.

If you need to change any configurations later run the `cushion-backend-init` script.

<p align="center"><img src="https://cushiondb.github.io/img/cushion-backend-init.gif"></p>

Feel free to add `./bin/cushion-backend-start` to your PATH so you don't have to retype it every time.

<p align="center"><img src="https://cushiondb.github.io/img/cushion-backend-start.gif"></p>

# The Team

[Avshar Kirksall]() *Software Engineer* Brooklyn, NY

[Jaron Truman]() *Software Engineer* Las Vegas, NV

[Daniel Rote]() *Software Engineer* Seattle, WA
