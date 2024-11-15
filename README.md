# Glue 4.0 Dev Container

Dev Container Setup for AWS Glue 4.0 Development

## Contents

The Dev Container is configured to leverage Docker Compose to start two services:

* AWS Glue 4.0 Local Development
* Moto Server

## Usage

To use the Dev container, copy the following items to your project:

* .devcontainer
* docker-compose.yml

Once added to your project, start the services using the following:

```command
docker compose up -d
```

This will start the Glue Service including the Jupyter Server and also start a Moto Server in the same network.
