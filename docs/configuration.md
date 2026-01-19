# Configuration

## Environment Variables

### AI Agent (.env)
```bash
GEMINI_API_KEY=your_gemini_api_key
POSTGRES_HOST=localhost
POSTGRES_PORT=5432
GITHUB_TOKEN=your_github_token
```

### Backstage (.env)
```bash
BACKEND_BASE_URL=http://localhost:7007
APP_BASE_URL=http://localhost:3000
GITHUB_ORG=your_github_org
GITHUB_REPO=your_template_repo
POSTGRES_HOST=localhost
```

## GitHub Setup

1. Create a GitHub Personal Access Token
2. Configure repository permissions
3. Set up OAuth app for Backstage authentication

## Database Setup

PostgreSQL is required for:
- Analysis history storage
- GitHub configuration persistence
- Backstage catalog data
