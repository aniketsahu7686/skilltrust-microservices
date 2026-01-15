# SkillTrust – Microservices Infrastructure (Week-1)

This repository contains the **infrastructure layer** for SkillTrust,
a real-world microservices-based hiring & interview platform.

## Tech Stack
- PostgreSQL – Relational Database
- Kafka + Zookeeper – Event Streaming
- MinIO – S3-compatible Object Storage
- Nginx – API Gateway
- Docker Compose – Container Orchestration

## Services (Planned)
- Auth Service
- User Service
- Job Service
- Interview Service
- Test Service
- Report Service
- Payment Service
- Notification Service

## Architecture (High Level)

Client  
→ Nginx API Gateway  
→ Microservices  
→ PostgreSQL / Kafka / MinIO  

## How to Run (Week-1)

```bash
docker-compose down
docker-compose up -d
