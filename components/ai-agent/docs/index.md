# Infrastructure AI Agent

Servicio de IA para generación automática de templates AWS usando Gemini AI.

## Funcionalidades

- Procesamiento de texto para detectar servicios AWS
- Análisis de imágenes de arquitectura
- Generación automática de templates de Backstage
- Integración con GitHub para publicación

## API Endpoints

- `POST /process-text` - Procesar descripción de texto
- `POST /process-image` - Procesar imagen de arquitectura
- `GET /health` - Estado del servicio

## Tecnologías

- FastAPI
- Python 3.11
- Google Gemini AI
- PostgreSQL
