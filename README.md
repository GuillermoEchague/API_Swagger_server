# Desarrollo de HTML para publicar la DOC de la api

```bash
# Intalación library
npm install -g redoc-cli

# Construcción del html (*.json o *.yaml)
redoc-cli bundle -o index.html openapi.yaml

```