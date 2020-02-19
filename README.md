# Builder Docker Image

This project contains the docker image used as part of [Chainlink](https://github.com/smartcontractkit/chainlink)'s Continuous Integration (CI).

It is based on the baidu SGX builder image and adds Go 1.12, Node 12.16.1 and Yarn 1.22.0.

On merges to master it publishes a [docker image](https://hub.docker.com/r/smartcontract/builder).
