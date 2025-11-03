# AI Document Platform

Microservice-based document processing platform with OCR and ML classification.

## Repositories

- 📱 [ai-platform-frontend](https://github.com/document-ai-platform/frontend) - React UI with Express server
- ⚙️ [ai-platform-backend](https://github.com/document-ai-platform/backend) - Spring Boot API
- 🤖 [ai-platform-ml-service](https://github.com/document-ai-platform/ml-service) - Python ML service
- 🐳 [ai-platform-infrastructure](https://github.com/document-ai-platform/infrastructure) - Docker & deployment

## Quick Start
```bash
# Clone all repos
git clone https://github.com/document-ai-platform/backend.git
git clone https://github.com/document-ai-platform/ml-service.git
git clone https://github.com/document-ai-platform/frontend.git
git clone https://github.com/document-ai-platform/infrastructure.git

# Move to infrastructure repo
cd infrastructure

# Start everything
./scripts/start.sh
```

Visit http://localhost:3000
