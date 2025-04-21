# 🎬 NextFlick

Este proyecto tiene como objetivo proporcionar a los usuarios una plataforma intuitiva para **gestionar y organizar las películas que desean ver**. La aplicación permite a los usuarios autenticarse, agregar películas a una lista personalizada, eliminarlas o marcarlas como vistas.

---

## 🛠 Tecnologías Utilizadas

### 🌐 Frontend – [React](https://reactjs.org/)
React es una biblioteca de JavaScript para construir interfaces de usuario. Se utiliza para crear una aplicación **SPA (Single Page Application)** con una navegación fluida y rápida.

Características principales:
- Componentes reutilizables
- Gestión del estado con hooks
- Enrutamiento con `react-router-dom`
- Comunicación con el backend usando `axios`

---

### 🖥️ Backend – [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/)
Node.js es un entorno de ejecución para JavaScript en el servidor, y Express es un framework minimalista que permite definir rutas, middleware y manejar peticiones HTTP de forma sencilla.

Características:
- Autenticación de usuarios (login y registro)
- Rutas protegidas con tokens JWT
- Conexión a base de datos MySQL
- Endpoints RESTful

---

### 🗄️ Base de Datos – [MySQL](https://www.mysql.com/)
Se utiliza una base de datos relacional para almacenar la información de usuarios, películas y sus listas personalizadas.

Tablas principales:
- `users` (información de usuarios)
- `movies` (películas obtenidas desde la API)
- `user_movies` (relación entre usuarios y películas)

---

### 🎥 API Externa – [The Movie Database (TMDb)](https://www.themoviedb.org/)
La aplicación se integra con la API de TMDb para obtener datos actualizados sobre las películas, incluyendo:
- Título
- Sinopsis
- Póster
- Calificación

Para usar la API es necesario crear una cuenta gratuita en [TMDb](https://www.themoviedb.org/) y generar una API Key.

---

## 🚀 Funcionalidades Principales

- Registro e inicio de sesión de usuarios
- Añadir películas a la lista de "Por ver"
- Marcar películas como vistas
- Eliminar películas de la lista
- Ver detalles de cada película usando la API de TMDb
- Interfaz limpia y fácil de usar

---

## 📦 Instalación del proyecto

1. Clona este repositorio:

```bash
git clone https://github.com/Piero2023/NextFlick.git


---


## 👨‍💻 Autor

Este proyecto fue desarrollado por **Piero Ramírez Esteban**, desarrollador web con interés en proyectos fullstack y en constante aprendizaje.

Puedes encontrarme en:

- 💻 GitHub: [https://github.com/Piero2023](https://github.com/Piero2023)  
- 💼 LinkedIn: [https://www.linkedin.com/in/pieroramirezesteban/](https://www.linkedin.com/in/pieroramirezesteban/)