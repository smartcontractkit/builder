# Builder Docker Image

This project contains the docker image used as part of [Chainlink](https://github.com/smartcontractkit/chainlink)'s Continuous Integration (CI).

It is based on the baidu SGX builder image and adds Go 1.14, Node 10.16.3 and Yarn 1.17.3.

On merges to master it publishes a [docker image](https://hub.docker.com/r/smartcontract/builder).
