## 🏗️ Arquitectura del Proyecto

El sistema está diseñado siguiendo una arquitectura cliente-servidor con separación por capas para mejorar la escalabilidad y el mantenimiento.

Frontend 
- Desarrollado con **HTML, CSS y JavaScript**.
- Funcionalidades:
  - Interfaz gráfica para la gestión de productos deportivos.
  - Catálogo de productos, carrito de compras y pasarela de pago.
  - Formularios de registro, inicio de sesión y gestión de pedidos.

 Backend 
- Lenguaje: Python
- Funcionalidades:
  - Gestión de usuarios, productos, ventas y reportes.
  - Exposición de API REST para comunicación con el frontend.
  - Manejo de autenticación y autorización de usuarios.

Base de Datos
- Motor: MySQL 
- Funcionalidades:
  - Almacenamiento de usuarios, inventario de implementos deportivos, ventas y facturación.
  - Relaciones entre tablas para clientes, productos y pedidos.


Flujo General
El usuario interactúa con el frontend.
El frontend envía solicitudes al **backend (API REST)**.
El backend procesa la lógica y consulta la **base de datos**.
El resultado es devuelto al frontend para mostrarlo al usuario.

Tecnologías Utilizadas

- Frontend: HTML5, CSS3, JavaScript, React.js  
- Backend: Node.js, Express.js  
- Base de Datos: MySQL  
- Control de versiones: Git y GitHub  
- Entorno de desarrollo: Visual Studio Code



Librerías Utilizadas

Frontend
- Axios: para realizar peticiones HTTP al backend.  
- React Router DOM: navegación entre páginas.  
- Bootstrap / Tailwind CSS: estilos y diseño responsivo.  

Backend
- Express: framework para la creación de APIs REST.  
- Cors: permitir comunicación entre frontend y backend.  
- Dotenv: manejo de variables de entorno.  
- Bcrypt.js: encriptación de contraseñas.  
- JSON Web Token (JWT): autenticación y autorización de usuarios.  
- Multer: manejo de subida de archivos (ej. imágenes de productos).  

 Base de Datos
- Sequelize / Mongoose / TypeORM: ORM para manejar las consultas a la base de datos.  
- MySQL2: librería para conexión directa con MySQL (si no usas ORM).  

