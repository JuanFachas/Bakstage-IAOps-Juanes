# ${{ values.name | title }}

${{ values.description }}

## 🚀 Arquitectura Serverless

### Servicios AWS
- **Lambda**: Funciones serverless (${{ values.runtime }})
- **API Gateway**: Endpoints REST
- **DynamoDB**: Base de datos NoSQL
- **S3**: Almacenamiento de archivos

### Configuración
- **Región**: ${{ values.aws_region }}
- **Runtime**: ${{ values.runtime }}

## 📦 Despliegue

```bash
# Instalar dependencias
npm install

# Desplegar con Serverless Framework
serverless deploy

# O con AWS SAM
sam build && sam deploy
```

## 🔧 Desarrollo

```bash
# Ejecutar localmente
serverless offline

# Testing
npm test
```

---
*Aplicación serverless generada por Infrastructure AI Platform*
