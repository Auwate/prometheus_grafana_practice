# Prometheus & Grafana Testing Grounds

This repository serves as a testing environment for learning **Prometheus** and **Grafana**, essential monitoring and visualization tools. The goal is to understand their core functionalities, configurations, and integrations for real-world applications.

## 📌 Project Overview

- **Prometheus**: Monitoring system & time-series database.
- **Grafana**: Interactive data visualization & dashboarding.
- **Dockerized Setup**: Easily run both tools in isolated containers.
- **Experiments**: Testing different configurations, alerting rules, and integrations.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- **Docker** & **Docker Compose**

### Running the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/Auwate/prometheus_grafana_practice.git
   cd prometheus_grafana_practice
   docker-compose up -d
   ```

2. Interacting:
    ```sh
    http://localhost:9090
    http://localhost:9000
    ```

3. Shutdown:
    ```sh
    docker-compose down
    ```

- localhost:9090 is for Prometheus
- localhost:3000 is for Grafana
- Default login is admin/admin for first-time login

# Changelog

## [Version: 0 - TEMPLATE] - 2025-02-19
### Added
- New features, functionalities, or configurations.

### Changed
- Updates to existing features or configurations.

### Fixed
- Bug fixes or performance improvements.

### Removed
- Deprecated features or unnecessary components.
