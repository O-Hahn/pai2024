# PAI 2024

## Install Docker

Install Docker [docker](https://docs.docker.com/engine/install/) on docker website.
Install Podman [podman](https://podman-desktop.io/downloads) 

## Clone this Repo

```bash
git clone https://github.com/O-Hahn/pai2024.git
```

## Install MQTT

Run docker-compose command in the mqtt-docker folder. 

```bash
docker-compose -p mqtt5 up -d
```

Install MQTTLatest instructions are [here](./mqtt-docker/mqtt-docker.md) on this repo.

## Install Node-Red

Run docker-compose command in the nodered-docker folder. 

```bash
docker-compose -p nodered up -d
```

Install Node-Red instructions are [here](./node-red-docker/nodered-docker.md) on this repo.
