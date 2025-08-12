# 🚀 Top 50 Docker Projects  

<div align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/github/stars/saeedmfat/top-50-docker-projects?style=for-the-badge" alt="GitHub Stars">
  <img src="https://img.shields.io/github/forks/saeedmfat/top-50-docker-projects?style=for-the-badge" alt="GitHub Forks">
  <img src="https://img.shields.io/badge/Projects-50+-success?style=for-the-badge" alt="Total Projects">
</div>

<br>

**A curated collection of production-grade Docker projects**  
Hands-on containerization examples ranging from beginner to advanced level with real-world implementation.

---

## � Core Projects

### 1. [Flask Dockerized App](https://github.com/saeedmfat/flask-docker-app)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Docker](https://img.shields.io/badge/Docker-Container-orange)
- **Key Skills**: Multi-stage builds • Environment variables • Volume mapping
- **Production Features**:
  - Optimized image size using Alpine base
  - Graceful shutdown handling
  - Healthcheck endpoint
- **Quick Start**:
```bash
docker compose up -d --build
```

### 2. [Nginx Static Website](https://github.com/saeedmfat/Nginx-Static-Website)
![Nginx](https://img.shields.io/badge/Nginx-1.25%2B-green)
![Performance](https://img.shields.io/badge/Optimized-A%2B-yellow)
- **Enterprise Patterns**:
  - Zero-downtime deployment
  - Brotli compression
  - Security headers
- **Usage**:
```bash
docker run -p 8080:80 --name nginx-site -v ./content:/usr/share/nginx/html:ro nginx
```

### 3. [Python Script Scheduler](https://github.com/saeedmfat/Python-Script-Scheduler-by-using-docker-fast-api-monitoring-)
[![Built with Python](https://img.shields.io/badge/Built%20with-Python%203.12-%233776AB?logo=python)](https://www.python.org/)
[![Powered by FastAPI](https://img.shields.io/badge/Powered%20by-FastAPI-%230099FF?logo=fastapi)](https://fastapi.tiangolo.com/)
[![Uses APScheduler](https://img.shields.io/badge/Uses-APScheduler-%23000000)](https://apscheduler.readthedocs.io/)
[![Containerized with Docker](https://img.shields.io/badge/Containerized%20with-Docker-%232496ED?logo=docker)](https://www.docker.com/)
![Monitoring](https://img.shields.io/badge/Prometheus-Enabled-blue)
- **Advanced Features**:
  - Log rotation
  - Resource constraints
  - Prometheus metrics endpoint
- **Deployment**:
```yaml
services:
  scheduler:
    deploy:
      resources:
        limits:
          cpus: '0.5'
          memory: 256M
```

---

<div align="center">
  <h3>🐳 Ready to containerize like a pro?</h3>
  <a href="https://github.com/saeedmfat/top-50-docker-projects/stargazers">
    <img src="https://img.shields.io/github/stars/saeedmfat/top-50-docker-projects?style=social" alt="Star">
  </a>
</div>
