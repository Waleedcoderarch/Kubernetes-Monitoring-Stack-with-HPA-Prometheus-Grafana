<h1>🚀 Kubernetes Monitoring Stack with HPA, Prometheus & Grafana</h1>

This project demonstrates how to deploy an application in Kubernetes, configure Horizontal Pod Autoscaling (HPA), and monitor the cluster using Prometheus and Grafana installed through Helm.

The goal of this project is to build a simple observability and autoscaling setup for Kubernetes workloads.

<h3>📌 Project Overview</h3>
<hr>
In this project, an Nginx application was deployed on Kubernetes using a Deployment resource.

CPU resource requests and limits were configured so that Kubernetes could monitor resource usage and scale the application when necessary.

A Horizontal Pod Autoscaler (HPA) was then configured to automatically scale pods based on CPU utilization.

To monitor the cluster and workloads, Prometheus and Grafana were installed using the kube-prometheus-stack Helm chart.

Prometheus collects metrics from the Kubernetes cluster

Grafana visualizes these metrics using interactive dashboards

This setup helps monitor cluster performance and workload behavior in real time.

<h3>📊 Monitoring Dashboard</h3>
<hr>
The Grafana dashboard provides real-time visibility into the Kubernetes cluster.

It allows monitoring of important metrics such as:

✔ Node CPU Usage
✔ Node Memory Usage
✔ Network Traffic
✔ Pod Metrics
✔ Cluster Resource Utilization


<img width="1507" height="770" alt="Screenshot 2026-03-05 014640" src="https://github.com/user-attachments/assets/0d4acc07-db22-4773-9dab-6da1a8e8ed77" />
<hr>

<img width="1515" height="853" alt="Screenshot 2026-03-05 014620" src="https://github.com/user-attachments/assets/18c82e1b-2b38-491f-a302-edcc0dd9d937" />

<hr>
<h3>🎯 Key Learnings</h3>

Through this project, I gained hands-on experience with:

• Deploying applications in Kubernetes
• Configuring Horizontal Pod Autoscaling (HPA)
• Installing tools using Helm
• Monitoring Kubernetes clusters with Prometheus
• Visualizing metrics with Grafana dashboards
• Troubleshooting Kubernetes service exposure issues
<hr>

<h3>✅ Conclusion</h3>

This project demonstrates a simple Kubernetes monitoring and autoscaling setup using Prometheus and Grafana.

It provides better visibility into cluster performance while enabling automatic scaling of workloads based on resource utilization.

This type of monitoring setup is essential for running reliable and scalable cloud-native applications.



