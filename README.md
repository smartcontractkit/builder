# Builder Docker Image

This project contains the docker image used to build [smartcontract/chainlink](https://github.com/smartcontractkit/chainlink).

It is based on the baidu SGX builder image and adds Go 1.11, Node 10.17.0 and Yarn 1.19.2.

Any merge to master is automatically deployed by Codeship. The docker tag on dockerhub is smartcontract/builder.
