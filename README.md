<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=header" width="100%" />
</p>

# Hi, I'm Jerônimo 👋

I'm an infrastructure and DevOps engineer.

Most of my work is around Proxmox, Kubernetes, infrastructure as code, and taking AI services from a developer's machine to a production cluster. On the backend side, I write async Python services with FastAPI, message queues, and PostgreSQL.

I also self-host more things than I probably should.

📍 Natal, RN — Brazil

---

## 🚀 What I work on

- **On-prem Kubernetes (k3s)**: NVIDIA GPUs shared via time-slicing, MetalLB, NGINX/HAProxy ingress, Longhorn/NFS storage, Harbor, remote BuildKit builds, a Pulp package cache, and a lot of other services (GitLab Runners, Sentry, Langfuse, MLflow, Keycloak, RabbitMQ…) managed with Helm and ArgoCD.
- **Infrastructure as code**: GCP/GKE (network, bastion, cluster) with Terraform and Ansible; Proxmox VMs with OpenTofu; Ansible playbooks for OS patching and etcd backups.
- **Document and audio pipelines**: GPU OCR (PaddleOCR), transcription with faster-whisper and speaker diarization (pyannote), NLP with spaCy, PII anonymization (Presidio), and legal document search on OpenSearch.
- **ML platform**: MLflow, Jupyter, Label Studio, CVAT, and Open WebUI + Ollama for experiments, labeling, and local LLMs.
- **Backend**: async FastAPI with RabbitMQ for long-running jobs, Valkey for caching, rate limiting, and WebSocket notifications, and PostgreSQL behind PgBouncer.
- **Observability**: kube-prometheus-stack, Loki/Alloy, DCGM, and cAdvisor, with my own dashboards and alerts for GPUs, volumes, nodes, and queues.
- **CI/CD**: pipelines on GitLab CI, GitHub Actions, and Jenkins that lint, type-check, test, scan, build, and push images, then bump the manifests that ArgoCD syncs.

---

## 🧰 Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)
![SQLModel](https://img.shields.io/badge/SQLModel-7E56C2)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E)
![asyncio](https://img.shields.io/badge/asyncio-3776AB?logo=python&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101)

**Quality & Testing**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?logo=ruff&logoColor=black)
![uv](https://img.shields.io/badge/uv-DE5FE9?logo=uv&logoColor=white)
![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?logo=precommit&logoColor=black)
![SonarQube](https://img.shields.io/badge/SonarQube-126ED3?logo=sonarqubeserver&logoColor=white)

**Containers & Kubernetes**
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?logo=podman&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![k3s](https://img.shields.io/badge/k3s-FFC61C?logo=k3s&logoColor=black)
![Helm](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=white)
![Harbor](https://img.shields.io/badge/Harbor-60B932?logo=harbor&logoColor=white)
![Longhorn](https://img.shields.io/badge/Longhorn-5F224B?logo=longhorn&logoColor=white)
![BuildKit](https://img.shields.io/badge/BuildKit-2496ED?logo=docker&logoColor=white)

**IaC, Cloud & Virtualization**
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?logo=opentofu&logoColor=black)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)

**Web Servers, Networking & OS**
![NGINX](https://img.shields.io/badge/NGINX-009639?logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?logo=apache&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-106DA9)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?logo=traefikproxy&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's_Encrypt-003A70?logo=letsencrypt&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?logo=pfsense&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?logo=opnsense&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?logo=debian&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Fedora](https://img.shields.io/badge/Fedora-51A2DA?logo=fedora&logoColor=white)

**CI/CD & GitOps**
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?logo=argo&logoColor=white)

**Data & Messaging**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?logo=postgresql&logoColor=white)
![PgBouncer](https://img.shields.io/badge/PgBouncer-336791)
![Redis](https://img.shields.io/badge/Redis-FF4438?logo=redis&logoColor=white)
![Valkey](https://img.shields.io/badge/Valkey-6983FF)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?logo=opensearch&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?logo=clickhouse&logoColor=black)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?logo=minio&logoColor=white)

**Observability**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?logo=grafana&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?logo=sentry&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A)

**AI, LLMs & Agents**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langgraph&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?logo=modelcontextprotocol&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991)
![RAG](https://img.shields.io/badge/Hybrid_RAG-5A67D8)

<details>
<summary><b>More: ML, Computer Vision, Security & Embedded</b></summary>

**Machine Learning & MLOps**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B0?logo=paddlepaddle&logoColor=white)
![Whisper](https://img.shields.io/badge/faster--whisper-412991)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

**Security & Identity**
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?logo=keycloak&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?logo=vault&logoColor=black)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?logo=trivy&logoColor=white)
![Presidio](https://img.shields.io/badge/Presidio-0078D4)

**Embedded**
![Arduino](https://img.shields.io/badge/Arduino-00878F?logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?logo=espressif&logoColor=white)

</details>

---

## 🌎 Languages

- 🇧🇷 **Portuguese**: native
- 🇺🇸 **English**: advanced

---

## 📊 GitHub Stats

<a href="https://github.com/jerbao">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=jerbao&theme=noctis_minimus&show_icons=true&hide_rank=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jerbao&theme=noctis_minimus&layout=compact" />
</a>

---

## 🌐 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jer%C3%B4nimo-rafael-386919418)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://instagram.com/jerb_rafael)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/jerbao)

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%" />
</p>
