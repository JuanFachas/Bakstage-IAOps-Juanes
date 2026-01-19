# API Reference

## Endpoints

### POST /process-text
Process text description of AWS architecture.

**Request:**
```bash
curl -X POST "http://localhost:8000/process-text" \
  -F "description=Web app with S3, CloudFront and Lambda"
```

**Response:**
```json
{
  "status": "success",
  "yaml_content": "...",
  "github_url": "...",
  "project_name": "ai-project-1234"
}
```

### POST /process-image
Process architecture diagram image.

**Request:**
```bash
curl -X POST "http://localhost:8000/process-image" \
  -F "image=@diagram.png"
```

### POST /configure-github
Configure GitHub repository settings.

### GET /history
Get analysis history.

### GET /health
Health check endpoint.
