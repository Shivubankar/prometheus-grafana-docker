# Prometheus + Grafana Docker Setup

This project sets up Prometheus and Grafana using Docker Compose for monitoring and alerting of Docker containers. It includes custom dashboards and alert rules to track system performance and detect anomalies.

## Prerequisites
- Docker
- Docker Compose

## Setup Instructions
1. Clone the repository  
   git clone https://github.com/Shivubankar/prometheus-grafana-docker.git  
   cd prometheus-grafana-docker

2. Start the services  
   docker-compose up -d

3. Access the services:  
   - Prometheus → http://localhost:9090  
   - Grafana → http://localhost:3000 (default login: admin/admin)

4. Stop the services  
   docker-compose down

## Project Structure
- docker-compose.yml → Service definitions  
- prometheus.yml → Prometheus configuration  
- README.md → Project documentation

## License
MIT License
