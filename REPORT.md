# Monitoring EC2 CPU Usage with Grafana

## Overview
This project sets up a Grafana dashboard to monitor EC2 instance CPU usage.

## Key Features
- Custom Grafana dashboard.
- Integrated with Prometheus for real-time monitoring.
- Stored JSON configuration for easy replication.

## Challenges
- SSH key issues when transferring JSON.
- Understanding Grafana data sources.

## Solutions
- Used SCP to securely transfer files.
- Configured Prometheus as the data source.

