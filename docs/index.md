# Infrastructure AI Platform

## Overview

The Infrastructure AI Platform is an intelligent system that automatically analyzes AWS architecture descriptions and generates Backstage catalog entries.

## Features

- **Text Analysis**: Process natural language descriptions of AWS architectures
- **Image Analysis**: Analyze architecture diagrams using AI vision
- **Backstage Integration**: Automatic catalog entry generation
- **GitHub Integration**: Save projects directly to repositories
- **Template System**: Generate complete project structures

## Quick Start

1. Access the AI Agent at http://localhost:8000
2. Configure your GitHub repository in the settings
3. Process your architecture description or diagram
4. View the generated project in Backstage

## Architecture

The platform consists of three main components:

- **AI Agent**: FastAPI backend with Gemini AI integration
- **Backstage**: Internal Developer Platform for catalog management
- **PostgreSQL**: Database for persistence and configuration
