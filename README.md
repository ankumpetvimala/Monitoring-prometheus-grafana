# 🚀 Container Monitoring with Prometheus & Grafana

This project sets up a container monitoring stack using **Prometheus**, **Grafana**, **Node Exporter**, and **cAdvisor** with **Docker Compose**.

---

## 📁 Stack Overview

* **Prometheus**: Metrics collection
* **Grafana**: Dashboard visualization
* **Node Exporter**: Host metrics
* **cAdvisor**: Container metrics

---

## 📆 How to Run

docker compose up -d

Access the services:

* **Prometheus** → [http://localhost:9090](http://localhost:9090)
* **Grafana** → [http://localhost:3000](http://localhost:3000)

  * **Username:** `admin` | **Password:** `admin`

---

## 📊 Dashboards

Imported Grafana dashboards:

* **Node Exporter Full** (Dashboard ID: `1860`)
* **Docker Container Overview** (Dashboard ID: `193` or `14282`)

### Grafana Dashboard

![Grafana Dashboard](screenshots/grafana-dashboard.png)

### Prometheus Query ("up")

![Prometheus up](screenshots/prometheus-up-query.png)

### Prometheus Targets

![Prometheus Targets](screenshots/prometheus-targets.png)

---

## ✅ Status

| Component     | Status    |
| ------------- | --------- |
| Prometheus    | ✅ Running |
| Grafana       | ✅ Running |
| Node Exporter | ✅ UP      |
| cAdvisor      | ✅ UP      |

---


