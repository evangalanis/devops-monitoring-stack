# DevOps Monitoring Stack (Docker + Prometheus + Grafana)

## Overview

This project demonstrates a simple monitoring stack running on an Ubuntu Server using Docker containers.

It collects system metrics and visualizes them through dashboards.

---

## Architecture

Node Exporter → Prometheus → Grafana

* Node Exporter collects system-level metrics (CPU, RAM, disk, network)
* Prometheus scrapes and stores the metrics
* Grafana visualizes the data in dashboards

---

## Technologies Used

* Docker
* Prometheus
* Grafana
* Node Exporter
* Ubuntu Server

---

## Project Structure

* docker-compose.yml
* prometheus.yml
* README.md

---

## How to Run

```bash
docker-compose up -d
```

---

## Access

Prometheus:
http://localhost:9090

Grafana:
http://localhost:3000

---

## Grafana Login

username: admin
password: admin

---

## Dashboard

Import dashboard:

ID: 1860
Name: Node Exporter Full

---

## What This Project Demonstrates

* Containerized monitoring setup
* Metrics collection and visualization
* Basic DevOps workflow using Docker
* Infrastructure observability fundamentals

