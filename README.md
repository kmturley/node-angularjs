# node-angularjs

Docker image for sites which need to build/run:

* NodeJS 8.x
* Angular 1.x
* Chrome (testing)

## Installation

    docker build -t "kmturley:node-angularjs" .

## Usage

Within your own Dockerfile:

    FROM: kmturley/node-angularjs

Within a CI pipeline:

    image: kmturley/node-angularjs

## Contact

For more information please contact kmturley
