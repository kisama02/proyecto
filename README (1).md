
# 📚 Registro de Alumnos

Aplicación web **fullstack** para registrar, editar y visualizar información de alumnos, desarrollada con **ReactJS** en el frontend y **PHP** con conexión a base de datos en el backend.

---

## 👨‍💻 Autores

- **Fabio Imanol Trigoso**
- **Jorge Mamani**

---

## 🧱 Estructura del Proyecto

```
📁 Backend-php/
  └── bd/
      └── configBD.php      # Configuración de conexión a base de datos
  └── index.php             # Punto de entrada para las peticiones al backend

📁 Frontend/
  └── src/
      ├── assets/           # Recursos como imágenes o íconos
      ├── components/       # Componentes de React como formularios y listas
      │   ├── FormularioAlumno.jsx
      │   ├── FormularioEditarAlumno.jsx
      │   ├── HomePage.jsx
      │   ├── ListAlumno.jsx
      │   └── Titulo.jsx
      ├── App.jsx           # Estructura principal de la app
      ├── App.css           # Estilos generales
      └── main.jsx          # Punto de inicio de React
  └── index.html            # HTML base
  └── vite.config.js        # Configuración del proyecto Vite
```

---

## 🛠️ Tecnologías utilizadas

- ReactJS (con Vite)
- PHP
- MySQL 
- CSS
- JavaScript 

---

## 🚀 Funcionalidades

- ✅ Registro de nuevos alumnos
- 📝 Edición de datos de alumno
- 🗑️ Eliminación de registros
- 📋 Visualización de la lista de alumnos
- 🎓 Selección de curso, sexo y si habla inglés
- 🔗 Conexión a base de datos vía backend en PHP

---

## ▶️ Cómo ejecutar el proyecto

### Frontend

```bash
cd Frontend
npm install
npm run dev
```

### Backend

1. Instala XAMPP, Laragon o tu entorno preferido con Apache y MySQL.
2. Coloca la carpeta `Backend-php` dentro de `htdocs` o el directorio correspondiente.
3. Crea una base de datos y actualiza `configBD.php` con tus credenciales y nombre de base de datos.
4. Accede desde el navegador a: `http://localhost/Backend-php/index.php`

---


## 🔧 Posibles mejoras

- Autenticación de usuarios
- Validaciones más estrictas en los formularios
- Manejo de errores del servidor
- Diseño responsive (adaptable a móviles)
- Paginación y filtros para la lista de alumnos
- Exportación de datos

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos.

