cat <<EOF > README.md
# Prometheus & Grafana Monitoring with Docker

This project sets up **Prometheus**, **Node Exporter**, and **Grafana** using Docker Compose to monitor system metrics in real time.

---

## Features
- **Prometheus**: Time-series database & monitoring
- **Node Exporter**: Collects Linux system metrics
- **Grafana**: Visualizes metrics with dashboards

---

## Project Structure
\`\`\`
.
├── docker-compose.yml
├── prometheus.yml
└── README.md
\`\`\`

---

## How to Run
1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/YOUR_USERNAME/prometheus-grafana-docker.git
   cd prometheus-grafana-docker
   \`\`\`
2. Start the services:
   \`\`\`bash
   docker-compose up -d
   \`\`\`
3. Access the dashboards:
   - **Prometheus**: http://localhost:9090
   - **Node Exporter**: http://localhost:9100/metrics
   - **Grafana**: http://localhost:3000 (user: admin, pass: admin)

---

## Example Prometheus Query
\`\`\`
node_filesystem_avail_bytes
\`\`\`

---

## Stop the Services
\`\`\`bash
docker-compose down
\`\`\`

---

## Author
Shivakumar SH
EOF
