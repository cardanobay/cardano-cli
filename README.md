# The Easy Peasy Cardano CLI

* We are currently in the FF (Friends & Family testnet) phase, so this guide is a work in progress. More detailed informations and concrete use cases to run a node will follow.

## How to use the CLI ?

You can grab the latest [fully statically linked binary](https://github.com/cardanobay/cardano-builder) in our [release page](https://github.com/cardanobay/cardano-cli/releases), or run it inside our very small container.
The container is based on [the scratch image](https://hub.docker.com/_/scratch "The Scratch Image"), which is basically **an empty image**.

### Pulling the container
```
docker pull cardanobay/cardano-cli:latest
```

### Running the container
```
docker run \
  --name cardano-cli \
  --rm \
  cardanobay/cardano-cli:latest <commands>
```

## Contact

Admin email : pascha+cardanobay@protonmail.com \
Website : https://www.cardanobay.com \
Website: https://k8s-pool.subnet.dev \
Docker Hub : https://hub.docker.com/r/cardanobay/cardano-cli \
Github : https://github.com/cardanobay/cardano-cli

