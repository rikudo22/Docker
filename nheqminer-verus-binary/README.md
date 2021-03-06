# Dockerfile for nheqminer-veruscoin

For more info see one of these websites: 

 * https://veruscoin.io
 * https://github.com/veruscoin

This flavour of `nheqminer-verus` will download and use the prebuilt binaries for the `v0.8.2` release from https://github.com/veruscoin/nheqminer/releases

## Prerequisites

[Docker](https://docs.docker.com/install/), ~200MB of disk space and the contents of this directory.

## Building the Docker image

Easiest way to get up and running:

```
git clone https://github.com/bloodynora/docker
cd docker/nheqminer-verus-binary
./build.sh
<edit nheqminer.conf to suit your needs>
./run.sh
```

## Looking for a pool? 

 * [pool.veruscoin.io](https://pool.veruscoin.io) is the 5% fee community pool, donating all of it directly to the VerusCoin Foundation.
 * A list of other mining pools is on the [VerusCoin website](https://veruscoin.io)

## Did this help you? 

Consider donating!

```
VRSC: RJgMwyavimFjJ6DtgdkuxxUqWCuKbpf8rp
```