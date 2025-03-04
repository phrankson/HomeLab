# 🚀 Homelab: Kubernetes GitOps Setup  

Welcome to my homelab repository! This setup is designed to run a **GitOps-driven** Kubernetes environment using **FluxCD**. The goal is to self-host applications efficiently while leveraging cloud-native best practices.  

## Key Features & Goals

* **Infrastructure as Code (IaC):** Everything is managed through Git, ensuring reproducibility and version control.
* **Automated Deployments:** Flux automatically synchronizes my cluster with the Git repository, enabling seamless updates.
* **Secure Access:** Cloudflare Tunnel provides secure and reliable access to my applications without exposing my home network.
* **Comprehensive Monitoring:** kube-prometheus-stack allows me to monitor the health and performance of my cluster and applications.
* **Learning & Experimentation:** This homelab serves as a platform for me to explore new technologies and deepen my understanding of Kubernetes and cloud-native practices.

## 🏡 Homelab Infrastructure  
- **Hardware**:  
  - Raspberry Pi 3B  
  - Dell XPS Laptop  

- **Kubernetes Distribution**:  
  - [K3s](https://k3s.io/) – Lightweight Kubernetes for edge and home lab environments  

- **Networking & Exposure**:  
  - [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/) – Secure, remote access without opening ports  

- **Secrets Management**:  
  - [SOPS with Age](https://github.com/mozilla/sops) – Securely encrypts Kubernetes secrets  

## 🔄 GitOps with FluxCD  
This homelab follows the **monorepo** approach with FluxCD, meaning all Kubernetes manifests and configurations are stored in a single repository and automatically applied to the cluster.  

## 🔍 Monitoring & Observability  
- [Kube-Prometheus-Stack](https://github.com/prometheus-operator/kube-prometheus) – Prometheus, Grafana, and Alertmanager for full-stack monitoring  
- **(Next) Add Loki & Tempo for full observability**  

## 📚 Self-Hosted Applications  
- [Linkding](https://github.com/sissbruecker/linkding) – Self-hosted bookmarking service   

## 🎯 Future Plans  
- Extend monitoring with **Loki**   
- Deploy additional self-hosted services  
- Automated Backups
- Adding dedicated NAS
- Adding VPN Server on HomeLab
- Cert Manager

## 💡 Why This Project?  
This homelab is more than just a collection of hardware and software. It's a testament to my passion for learning and experimentation. By embracing GitOps and Kubernetes, I'm building a resilient and scalable platform for my personal projects. This project demonstrates my ability to:

* Design and implement a Kubernetes-based infrastructure.
* Utilize GitOps principles for automated deployments.
* Manage secrets securely.
* Monitor and troubleshoot a complex system.
* Document and present a technical project.
 

---

