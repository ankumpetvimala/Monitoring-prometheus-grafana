# Monitoring with Prometheus & Grafana

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

![Grafana Dashboard]

![grafana dashboard](https://github.com/user-attachments/assets/38d2c99a-3540-4349-8326-a6445ad6717d)

### Prometheus Query ("up")

![Prometheus up]

![prometheus up](https://github.com/user-attachments/assets/50464e5d-5272-4ec9-9fe6-b1983fd585f6)


### Prometheus Targets

![Prometheus Targets]

![Prometheus targets](https://github.com/user-attachments/assets/01527275-4f57-44df-97b7-cb717296a984)

---

## ✅ Status

| Component     | Status    |
| ------------- | --------- |
| Prometheus    | ✅ Running |
| Grafana       | ✅ Running |
| Node Exporter | ✅ UP      |
| cAdvisor      | ✅ UP      |

---


