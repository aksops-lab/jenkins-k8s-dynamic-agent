# Jenkins on Kubernetes with Dynamic Agents PoC

This repository demonstrates a **Proof of Concept (PoC)** for running Jenkins on Kubernetes with **dynamic worker pods** that are provisioned on-demand to execute CI/CD jobs.

---

## Features

- Jenkins Master deployed on Kubernetes.
- Dynamic Jenkins agents provisioned as **Kubernetes pods**.
- Kubernetes plugin integration in Jenkins for scaling workers automatically.
- CI/CD pipelines can run multiple jobs in parallel without manually managing agents.
- Dockerized setup for local development or cloud deployment.

