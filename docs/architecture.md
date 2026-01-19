# Architecture

## System Overview
```
User → AI Agent (:8000) → Gemini AI → GitHub → Backstage (:3000)
```

## Components
- **AI Agent**: Process inputs, generate YAML
- **Backstage**: Catalog management, templates
- **PostgreSQL**: Data persistence
