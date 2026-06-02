# CyberShield: Infrastructure Monitoring Dashboard

A real-time infrastructure monitoring and observability dashboard built using Grafana, Prometheus, and Windows Exporter.

## Features

- CPU Utilization Monitoring
- Memory Usage Tracking
- Available Memory Monitoring
- System Uptime Monitoring
- Running Process Monitoring
- Custom PromQL Queries
- Docker-based Deployment

## Tech Stack

- Grafana
- Prometheus
- Windows Exporter
- Docker

## Architecture

Windows Exporter → Prometheus → Grafana

## Dashboard Metrics

- CPU Usage %
- Memory Usage %
- Available Memory (GB)
- System Uptime
- Running Processes

## Setup

```bash
docker compose up -d
```

Grafana:
http://localhost:3000

Prometheus:
http://localhost:9090