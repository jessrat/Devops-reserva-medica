# Proyecto DevOps – Reserva médica

Página estática de demostración para Centro Médico ABC, servida con Nginx en Docker. No incluye API ni base de datos.

## Ejecutar
```bash
docker compose up -d --build
docker compose ps
```
Abrir http://localhost:8080.

## Monitorear
```bash
docker logs reserva-medica-web
docker stats --no-stream reserva-medica-web
```
## Detener
```bash
docker compose down
```
No usar datos personales reales. No hay credenciales. `.gitignore` excluye `.env` y logs.