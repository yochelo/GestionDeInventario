# ⚙️ Gestión de Inventarios

Sistema completo (backend + frontend) desarrollado para ingresar, editar y controlar el stock hospitalario a partir de archivos Excel.  
No solo genera una base de datos lista para consultas y trazabilidad, sino que también permite moldear, actualizar y comparar los elementos de forma dinámica y visual.

> ⚠️ **Código no incluido por motivos estratégicos. Se comparte bajo solicitud profesional.**

## 📽️ Demo en video

🎥 [Ver video explicativo en YouTube](https://www.youtube.com/watch?v=KJV5SbuOCN0&t=16s)

## 🧩 Funcionalidades principales

- 📥 Importación masiva de insumos desde Excel.
- 🗂️ Generación automática de base de datos relacional.
- ✏️ Interfaz para agregar, editar y dar de baja elementos.
- 🧠 Comparación inteligente entre versiones: si se importa una nueva planilla con posibles cambios, el sistema detecta diferencias (por ejemplo, cambio de ubicación, sector, estado) y permite decidir qué atributo conservar (el actual o el nuevo).
- 📲 Generador de QR único por ítem, listo para impresión.
- 📷 Escaneo de QR desde celular autorizado, que abre un modal con todos los datos relevantes del equipo: número de serie, estado, observaciones, y más.

## 🔧 Tecnologías usadas

- JavaScript (frontend + lógica de backend)
- HTML / CSS
- Librerías para generación de QR y lectura de archivos Excel
- SQLite (gestión local de base de datos)
- LocalStorage (modo offline)
- Node.js (estructura de archivos y lógica)
- Excel como punto de partida para estructurar y actualizar la base

## 📁 Estructura del proyecto (en versión completa)

```text
/GESTION
├── /public
│   └── GestionDeInventario.html
├── /node_modules
├── /sqlite
├── index.js
├── inventarios.db
├── varios archivos JSON
├── package.json
└── README.md
```

📌 Esta estructura representa una versión funcional. Algunas carpetas y archivos fueron omitidos por simplicidad o privacidad.

## 💬 Nota

Este repositorio muestra solo una descripción general del sistema.  
El código fuente completo puede ser solicitado en entrevistas o contextos profesionales.

---

📧 mazzara.marcelo@gmail.com  
🌍 Ciudad de Buenos Aires, Argentina
