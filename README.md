🚀 Kubernetes Monitoring Stack with HPA, Prometheus & Grafana

This project demonstrates how to deploy an application in Kubernetes, configure Horizontal Pod Autoscaling (HPA), and monitor the cluster using Prometheus and Grafana installed through Helm.

The purpose of this project is to build a simple observability and autoscaling setup for Kubernetes workloads, enabling better visibility into cluster performance and automated scaling based on resource usage.

📖 Project Overview

In this practical implementation, an Nginx application was deployed on Kubernetes using a Deployment resource.

CPU resource requests and limits were configured so Kubernetes could monitor resource utilization and scale the application when required.

A Horizontal Pod Autoscaler (HPA) was then configured to automatically scale the number of pods based on CPU utilization.

To monitor the Kubernetes cluster and application workloads, Prometheus and Grafana were installed using the kube-prometheus-stack Helm chart.

Prometheus collects metrics from Kubernetes components and workloads.

Grafana visualizes these metrics through interactive dashboards.

This setup provides insights into cluster health and application performance.

📊 Monitoring Dashboard

Grafana dashboards provide real-time visibility into the Kubernetes cluster.

These dashboards allow monitoring of key infrastructure metrics such as:

Node CPU Usage

Node Memory Usage

Network Traffic

Pod Metrics

Cluster Resource Utilization

These metrics help in understanding cluster performance and identifying potential bottlenecks.

(Dashboard screenshots can be added below)

/screenshots/dashboard1.png
/screenshots/dashboard2.png
🏗️ Architecture
Application Deployment (nginx)
        │
        │
Metrics Server
        │
        │
Horizontal Pod Autoscaler
        │
        │
Prometheus (Metrics Collection)
        │
        │
Grafana (Metrics Visualization)
🎯 Key Learnings

Through this project, the following concepts were implemented and learned:

Deploying applications in Kubernetes

Configuring Horizontal Pod Autoscaling (HPA)

Installing applications using Helm

Monitoring Kubernetes clusters with Prometheus

Visualizing metrics using Grafana dashboards

Troubleshooting service exposure issues in Kubernetes

✅ Conclusion

This project demonstrates a basic Kubernetes monitoring and autoscaling setup using Prometheus and Grafana.

It enables better visibility into cluster performance while allowing Kubernetes to automatically scale workloads based on resource utilization.

Such monitoring and observability setups are essential for maintaining reliable and scalable cloud-native applications.
