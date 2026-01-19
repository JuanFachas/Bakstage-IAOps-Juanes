# Architecture

## System Overview

```
User → AI Agent (:8000) → Gemini AI → GitHub → Backstage (:3000)
```

## Components

### AI Agent
- **Technology**: FastAPI + Python
- **Port**: 8000
- **Function**: Process text/image inputs, generate YAML, save to GitHub

### Backstage
- **Technology**: Node.js + TypeScript
- **Ports**: 3000 (UI), 7007 (API)
- **Function**: Catalog management, templates, documentation

### Database
- **Technology**: PostgreSQL
- **Port**: 5432
- **Function**: Store analysis history, GitHub configurations

## Data Flow

1. User submits architecture description
2. AI Agent processes with Gemini API
3. Generated YAML is validated
4. Project structure is created in GitHub
5. Backstage auto-discovers the new component
