# TheHive-Cortex-Misp
# Docker Compose Setup for TheHive, Cortex, and MISP

This repository contains a Docker Compose configuration file (`docker-compose.yml`) for setting up TheHive, Cassandra, Elasticsearch, MinIO, Cortex, and MISP services. These services are crucial components for Security Operations Centers (SOCs) and threat intelligence management.

## Prerequisites

Before running the Docker Compose setup, ensure that you have Docker and Docker Compose installed on your system.

## Usage

1. Clone this repository to your local machine.
2. Navigate to the directory containing the `docker-compose.yml` file.
3. Run the following command to start the services:

    ```bash
    docker-compose up -d
    ```

   The `-d` flag runs the containers in detached mode, meaning they will run in the background.
