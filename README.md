# API Testing – JSONPlaceholder

## 📖 Descripción
Pruebas de **API REST** usando **Postman + Newman** sobre el servicio público JSONPlaceholder.  
Validación de endpoints GET, POST, PUT y DELETE con aserciones.

---

## 📂 Contenido
- **jsonplaceholder.postman_collection.json** → colección con requests y tests.
- **jsonplaceholder.postman_environment.json** → variables de entorno.
- **package.json** → script de ejecución con Newman.

---

## 🛠️ Herramientas
- Postman
- Newman (CLI)
- Node.js

---

## 🚀 Cómo ejecutar
```bash
# Instalar dependencias
npm install

# Ejecutar pruebas y generar reporte
npm run test

# Reporte HTML en ./newman/report.html
