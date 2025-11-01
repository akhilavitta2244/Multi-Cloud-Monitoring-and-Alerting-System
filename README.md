# 🌐 Multi-Cloud Monitoring and Alerting System

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Terraform](https://img.shields.io/badge/Terraform-v1.8-blue)
![Grafana](https://img.shields.io/badge/Grafana-10.1-orange)
![Prometheus](https://img.shields.io/badge/Prometheus-2.53-red)

## 📖 Overview
An end-to-end **monitoring and alerting system** integrating Prometheus and Grafana with **AWS CloudWatch**, **Azure Monitor**, and **GCP Operations Suite**.  
It centralizes multi-cloud observability and sends real-time alerts to Slack and PagerDuty.

## 🏗️ Architecture
![Monitoring Architecture](./images/monitoring-architecture.png)

## 🧰 Tech Stack
- **Infrastructure as Code:** Terraform  
- **Monitoring:** Prometheus, CloudWatch, Azure Monitor, GCP Operations  
- **Visualization:** Grafana  
- **Alerting:** Slack, PagerDuty  
- **Clouds:** AWS, Azure, GCP

## ⚙️ Setup Instructions
```bash
git clone https://github.com/yourusername/multi-cloud-monitoring-system.git
cd multi-cloud-monitoring-system
