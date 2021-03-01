## Docker - Grafana InfluxDB and Collectd with FritzBox plugin
This includes a preconfigured Collectd including the Pyhton plugin fritzcollectd, based on Docker. Also included a Docker-Compose file to get fast up and monitoring.

## The following examples / configs are included
* Docker-Compose-File
* Collectd-Config
* InfluxDB-Config and types.db for Collectd
* Grafana-Dashboard. 

## What you need to run this
* Basic understanding of Docker (Docker-Compose) and Grafana

## Getting started

1. Clone project
2. Configure docker-compose.yml
3. Create Fritzbox User (System - Fritz!Box User - User)
4. Run: "docker-compose up" or "docker-compose up -d" 
5. Go to http://dockerhostip:3000 and start setting up Grafana - Example Grafana-Dashboard can be found in the grafana-dashboard.json 

## Software used
* Ubuntu 18.04 LTS
* Collectd
* Python
* fritzcollectd

NOTES: 
If the Dashboards reloads to slow (no Data shown), increase the Docker Swap/RAM and CPU and/or reduce the Grafana Panels. 
