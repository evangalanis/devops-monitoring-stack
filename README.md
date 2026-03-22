# DevOps Monitoring Stack (Docker + Prometheus + Grafana)

A simple monitoring stack built on an Ubuntu Server VM using Docker.

## Stack

* Docker
* Prometheus
* Grafana
* Node Exporter

## Architecture

Node Exporter → Prometheus → Grafana

Node Exporter collects system metrics (CPU, RAM, disk).
Prometheus scrapes those metrics.
Grafana visualizes them in dashboards.

## Project Files

docker-compose.yml
prometheus.yml
README.md

## Run the stack

```
docker-compose up -d
```

## Access the services

Prometheus
http://localhost:9090

Grafana
http://localhost:3000

## Grafana login

username: admin
password: admin

## Dashboard

Import dashboard from Grafana.com

ID: 1860
Name: Node Exporter Full

This dashboard shows:

* CPU usage
* Memory usage
* Disk usage
* Network traffic
* System load
