# Anna Alcaide Portfolio
![DevOps](https://img.shields.io/badge/DevOps-Portfolio-blue)
![AWS](https://img.shields.io/badge/AWS-in_progress-orange)
![GCP](https://img.shields.io/badge/GCP-deployed-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-production-blue)
![Terraform](https://img.shields.io/badge/Terraform-IaC-purple)
![CI/CD](https://img.shields.io/badge/CI/CD-GitHub_Actions-black)

Welcome to my portfolio of DevOps and full-stack development projects. Here you'll find some of my featured projects with descriptions, technologies used, and screenshots of their functionality or pipelines.

---

## 1. Python URL Shortener (GCP + GKE)
![Pipeline](screenshots/python-url-shortener/pipeline.png)
- **Description:** A URL shortener built with Python and Docker, deployed on GKE. It allows you to shorten URLs and perform basic statistics tracking.
- **Features:**
- URL shortening service
- Containerized Python app deployed on GKE  
- Infrastructure as Code with Terraform
- CI/CD pipeline with GitHub Actions  
- Monitoring with Prometheus & Grafana  
- Exposed via LoadBalancer  
- **Technologies:** Python, Docker, Kubernetes, GCP (GKE), Cloud Run, ArgoCD.
- **Repository:** [python-url-shortener](https://github.com/sassenagh/python-url-shortener)
- **Status:** Functional with automated deployment on GKE.
- - **Pipeline image:** `pipeline.png` in `screenshots/python-url-shortener/`.

--

## 2. Node Image Resizer (AWS + EKS)
![Pipeline](screenshots/node-image-resizer/pipeline.png)
- **Description:** Image resizing service using Node.js. Supports image uploads and thumbnail generation.
- **Features:**
- Upload images via REST API
- Image resizing handled by background workers
- Storage in AWS S3
- GitOps deployment with Argo CD
- Infrastructure managed with Terraform
- **Technologies:** Node.js, Express, Docker, GitHub Actions.
- **Repository:** [node-image-resizer](https://github.com/sassenagh/node-image-resizer)
- **Status:** Functional, automated deployment, and integrated unit tests.
- **Pipeline image:** `pipeline.png` in `screenshots/node-image-resizer/`.

- ---

## 3. Kubernetes AI PR Bot (k8s + AI)
![PR Response](screenshots/k8s-ai-pr-bot/pr-response.png)
- **Description:** Bot that automatically comments on pull requests using AI. Deployed on Kubernetes with CI/CD on GitHub Actions.
- **Features:**
- Automatic review of Kubernetes PR diffs using OpenAI GPT-3.5 (optional)
- Detection of critical issues (privileged containers, :latest images)
- Suggestions for improvements (resource limits, health checks, namespace, deprecated APIs)
- Fallback review if OpenAI is not configured or quota is exhausted
- **Technologies:** Python, Kubernetes, GitHub Actions, OpenAI API.
- **Repository:** [k8s-ai-pr-bot](https://github.com/sassenagh/k8s-ai-pr-bot)
- **Status:** Functional, tested via pull requests.
- **Screenshot of the bot's response on PR:** `pr-response.png` in `screenshots/k8s-ai-pr-bot/`.

---

## Tech Stack

- **Cloud**: GCP, AWS  
- **Containers**: Docker, Kubernetes  
- **Infrastructure as Code**: Terraform  
- **CI/CD**: GitHub Actions  
- **Monitoring**: Prometheus, Grafana  
- **Languages**: Python, Node.js  

---

## About

This portfolio reflects practical experience building and deploying cloud-native applications with a strong DevOps focus.

---

## Contact

- **GitHub:** [https://github.com/sassenagh](https://github.com/sassenagh)
- **LinkedIn:** [https://www.linkedin.com/in/anaalcaideh](https://www.linkedin.com/in/anaalcaideh)

---

**Notes:**

- All screenshots are in the `screenshots/` folder, organized by project.
- Each project includes badges and links to its original repository.