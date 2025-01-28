Secret Examples

N8N_ENCRYPTION_KEY -> Qdrant API Key

```
kubectl create secret generic postgres-secrets \
  --from-literal=POSTGRES_USER=tu_usuario \
  --from-literal=POSTGRES_PASSWORD=tu_contraseña \
  --from-literal=POSTGRES_DB=n8n

kubectl create secret generic n8n-secrets \
  --from-literal=N8N_ENCRYPTION_KEY=tu_clave_encriptacion \
  --from-literal=N8N_USER_MANAGEMENT_JWT_SECRET=tu_jwt_secreto
```