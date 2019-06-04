# docker-compose-bla

To start the siwecos-business-layer on your local machine, install Docker and docker-compose,
clone this repo and run `docker-compose up` inside the repo's directory.

**NB: In most cases you don't need to use this repo!**<br>
Just use the hosted variant on https://siwecos.de or use the [SIWECOS/docker-compose-scanners]() for hosting the core functionality of SIWECOS by yourself.

## Usage in `staging` environment
Just change the `siwecos/siwecos-business-layer:latest` line within `docker-compose.yml` to `siwecos/siwecos-business-layer:develop` and run the `docker-compose up` command.
