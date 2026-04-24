# 🚀 UITJobs Docker Deployment

**UITJobs** is a comprehensive Full-stack recruitment platform—a hybrid of *ITViec* and *Glassdoor*—designed specifically for the **UIT-VNUHCM** ecosystem. The platform empowers candidates to discover career opportunities, review companies, and share interview insights. Simultaneously, it provides organizations with robust tools to post vacancies and manage applicants, all secured through Role-Based Access Control (RBAC).

Containerized with Docker, the system is optimized for seamless deployment and scalability.

## 🏗️ System Architecture

The project consists of three core services:
- **Backend (`uitjobs-be`)**: Handles business logic and API processing.
- **Frontend (`uitjobs-fe`)**: User interface built with Next.js/React.
- **Nginx Proxy (`nginx-proxy`)**: Orchestrates traffic and connects Frontend/Backend via port 80.

## 📋 Prerequisites

- **Docker** (v20.10 or higher)
- **Docker Compose** (v2 or higher)

## 🚀 Quick Start Guide

### 1. Clone the Repository
```bash
git clone https://github.com/Osticle/UITJobs-Docker-Container.git
cd UITJobs-Docker-Container
```

### 2. Deploy with Docker Compose

Pull the latest pre-built images from Docker Hub:
```bash
docker compose pull
```

Launch the system in detached mode:
```bash
docker compose up -d
```

### 3. Verify Status
Check if all containers are running correctly:
```bash
docker compose ps
```

## 🌐 Web Access

Once the deployment is successful, you can access the application at:
- **URL:** [http://localhost](http://localhost) or [http://127.0.0.1](http://127.0.0.1)

---

## 🛠️ Maintenance Commands

- **View logs:**
  ```bash
  docker compose logs -f
  ```
- **Stop the system:**
  ```bash
  docker compose down
  ```
- **Restart all services:**
  ```bash
  docker compose restart
  ```

## 📄 Additional Information
- **Main Repository:** https://github.com/thaihadefi/Innovation-Project
- **Docker Hub Images:** https://hub.docker.com/u/sugm4d1c
