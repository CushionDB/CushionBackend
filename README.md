# Overview

CushionBackend is the easiest way to start up CushionDB's backend and database. It includes the `docker-compose.yml` file that is used to build and run the [CushionServer](https://github.com/CushionDB/CushionServer) and [CushionCouch](https://github.com/CushionDB/CushionCouchDocker) images, and they install directly from DockerHub. Once you have the CushionBackend running head over here to download Cushion's client side portion  [CushionClient](https://github.com/CushionDB/CushionClient).

## Usage

Clone this repo, and in the repo's root folder run `./.bin/cushion-backend-start`. The first time this command it run it will prompt you for some information. Make sure that if you update any configuration you will need to update the cushionClient configuration as well.

If you need to change any configurations later run the `./.bin/cushion-backend-init` script.

<p align="center"><img src="https://cushiondb.github.io/img/cushion-backend-init.gif"></p>

run `./.bin/cushion-backend-teardown` to tear down the docker images.

<p align="center"><img src="https://cushiondb.github.io/img/cushion-backend-start.gif"></p>

# The Team

[Avshar Kirksall]() *Software Engineer* Brooklyn, NY

[Jaron Truman]() *Software Engineer* Las Vegas, NV

[Daniel Rote]() *Software Engineer* Seattle, WA
