# The Easy Peasy Cardano CLI

* We are currently in the FF (Friends & Family testnet) phase, so this guide is a work in progress. More detailed informations and concrete use cases to run a node will follow.

* I am running my node with buildah/podman, which is exactly the same as docker. So it may be possible you find some references to theses tools in this. If this is the case, just replace the terms "**buildah/podman**" by "**docker**"

## How to use the CLI ?

You can grab the latest fully statically linked cardano-cli in our [release page](https://github.com/cardanobay/cardano-cli/releases), or run it inside our very small container.
The container is based on [the scratch image](https://hub.docker.com/_/scratch "The Scratch Image"), which is basically **an empty image**.

### Pulling the container
```
docker pull cardanobay/cardano-cli:latest
```

### Pulling the container
```
docker run \
  --name cardano-cli \
  --rm \
  cardanobay/cardano-cli:latest <commands>
```

## Contact

Admin email : pascha+cardanobay@protonmail.com \
Website : https://www.cardanobay.com \
Docker Hub : https://hub.docker.com/r/cardanobay/cardano-cli \
Github : https://github.com/cardanobay/cardano-cli

