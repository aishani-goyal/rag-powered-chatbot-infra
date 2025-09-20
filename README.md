# RAG Chatbot Infrastructure

This repository contains the **infrastructure and configuration files** for deploying the RAG-Powered News Chatbot.  
It works alongside the [frontend](https://github.com/aishani-goyal/rag-powered-chatbot-frontend) and [backend](https://github.com/aishani-goyal/rag-powered-chatbot-backend) repositories.

## 📂 Contents

- **`docker-compose.yml`** – Defines services like Redis and Qdrant for local development and deployment.  
- **`package.json` / `package-lock.json`** – Project metadata and shared scripts.  
- **`.gitignore`** – Ensures unnecessary files and folders are excluded.  

## 🔧 Purpose

- Provides an isolated place to manage infrastructure configuration.  
- Simplifies running dependencies locally (Redis, Qdrant).  
- Prepares the project for easy extension to CI/CD pipelines or cloud infrastructure.  

## 🚀 Usage

**Clone this repo alongside the frontend and backend repos:**

```bash
git clone https://github.com/aishani-goyal/rag-powered-chatbot-infra.git
cd rag-powered-chatbot-infra
```

**Start Infrastructure Services**

```bash
docker-compose up -d
```

**Verify Services are Running**

```bash
docker ps
```

You should see containers for Redis and Qdrant running.

## 🌐 Related Repositories

- [Frontend Repo](https://github.com/aishani-goyal/rag-powered-chatbot-frontend)
- [Backend Repo](https://github.com/aishani-goyal/rag-powered-chatbot-backend)

**Note:** This repo only manages infrastructure. The application logic resides in the frontend and backend repositories.

## 📄 License

MIT License
