# PipelineIQ Notification Service

Independent repository staging folder for the PipelineIQ notification service.

## Build

```bash
docker build -t nimeshsv814/pipelineiq-notification-service:v1.0.0 -f services/notification-service/Dockerfile .
```

## Run

This service expects PipelineIQ environment variables from Kubernetes ConfigMap and Key Vault secrets.
