AWS RDS (Postgres) → FastAPI → Tu Pipeline → Analytics DB
     ↑                  ↑            ↑
  (Simula Prod)    (Tu API)    (Tu Sistema)


# Agrosima Data Pipeline

Data engineering pipeline for sales optimization and predictive analytics.

## Sprint 1: Basic Data Extraction
- Extract production data to local PostgreSQL
- Docker-based development environment
- Simple backup and restoration

## Setup
1. Copy `.env.example` to `.env` and configure your credentials
2. Run `docker-compose up -d`
3. Execute `./scripts/extract_data.sh`

## Project Status
- ✅ Sprint 1: Foundation Setup
- ⏳ Sprint 2: Error Handling  
- ⏳ Sprint 3: Production Ready