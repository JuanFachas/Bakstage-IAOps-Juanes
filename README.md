# Infrastructure AI Agent - Template IDP

Este repositorio contiene el catálogo de servicios generado automáticamente por el Infrastructure AI Agent.

## 📁 Estructura

```
├── catalog-info.yaml          # Catálogo principal
├── entities/                  # Entidades generadas por AI
│   ├── example-web-app.yaml  # Ejemplo de aplicación web
│   └── ...                   # Más arquitecturas generadas
└── README.md                 # Este archivo
```

## 🤖 Generación Automática

Las entidades en `entities/` son generadas automáticamente por el AI Agent cuando:

1. Se procesa una descripción de texto de arquitectura
2. Se analiza un diagrama de arquitectura
3. Se valida y guarda en este repositorio
4. Backstage las importa automáticamente

## 🔗 Integración

- **AI Agent**: http://localhost:8000
- **Backstage**: http://localhost:3000
- **Repositorio**: https://github.com/giovanemere/demo-infra-ai-agent-template-idp

## 📊 Uso

1. Accede al AI Agent en http://localhost:8000
2. Describe tu arquitectura o sube un diagrama
3. El YAML se genera y guarda automáticamente aquí
4. Backstage lo importa y muestra en el catálogo
