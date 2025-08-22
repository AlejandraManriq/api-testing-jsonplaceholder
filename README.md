# API Testing — JSONPlaceholder

> **Stack:** Postman + Newman (CLI).  
> **Objetivo:** Probar endpoints REST (GET/POST/PUT/DELETE) con aserciones y reportes.

## Requisitos
- Node.js 18+
- Postman (opcional para editar)
- `npm i` para instalar newman y reporter HTML

## Ejecutar
```bash
npm install
npm run test
# Reporte HTML: ./newman/report.html
```

## Estructura
- `jsonplaceholder.postman_collection.json`
- `jsonplaceholder.postman_environment.json`
- `package.json` (scripts de newman)
