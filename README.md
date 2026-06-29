# Linux Server Monitoring Dashboard

A real-time Linux server monitoring stack built with Docker, Prometheus, Grafana, and Node Exporter.

## What it does
- Monitors CPU, RAM, Disk, and Network usage in real time
- Stores metrics history with Prometheus
- Visualizes everything in a Grafana dashboard
- Alerts when CPU usage exceeds 80%

## Architecture
Ubuntu VM → Node Exporter → Prometheus → Grafana → Browser

## Tools Used
- Docker & Docker Compose
- Prometheus
- Grafana
- Node Exporter
- Ubuntu 26.04 LTS

## How to Run
1. Clone this repository
2. Run the stack:
   docker compose up -d
3. Open Grafana at http://your-server-ip:3000
4. Login with admin/admin
5. Import dashboard ID: 1860

## What I Learned
- Docker containerization and docker-compose
- Linux system metrics and monitoring concepts
- Prometheus scraping and PromQL queries
- Grafana dashboard configuration and alerting
- SSH server management and Linux administration
## Dashboard Screenshot
![Dashboard](dashboard.png)
