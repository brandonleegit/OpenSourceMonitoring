# OpenSourceMonitoring

Free and Open source monitoring configuration template for setting up Prometheus, Node Exporter, Grafana, and cAdvisor using Docker Compose.

## Steps to create in your environment

- You will need to install a Docker container host in your environment. 
- Also, install Docker Compose

Once you have the Docker prerequisites in place, create the directory structure in your home directory using the following commands:


mkdir -p promgrafnode/prometheus && \ 
mkdir -p promgrafnode/grafana/provisioning && \ 
touch promgrafnode/docker-compose.yml && \ 
touch promgrafnode/prometheus/prometheus.yml

## Clone down the example files

Using the example docker-compose.yml and prometheus.yml configuration files, you will just need to copy the contents into your docker-compose.yml and prometheus.yml created from the commands above.

## Create the containers

Once you have the directories create, navigate to the promgrafnode folder and issue the command **docker-compose up -d**
