
# Project 6: Monitoring Dashboard (Prometheus & Grafana)

This project sets up a complete monitoring stack using **Prometheus** for metrics collection and **Grafana** for visualization, orchestrated via **Docker Compose**.

## Services
- **Prometheus**: Runs on port `9090` to collect metrics.
- **Grafana**: Runs on port `3000` to create custom dashboards.

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd project-6-monitoring-dashboard

 2 Start the stack using Docker Compose:
   docker-compose up -d
   
 3 Access Prometheus at http://localhost:9090 and Grafana at http://localhost:3000.

