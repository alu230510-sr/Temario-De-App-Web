# Temario de Appweb :shipit:

---

## 1. Introducción y Fundamentos

### Introducción al desarrollo web
<img width="203" height="122" alt="image" src="https://github.com/user-attachments/assets/bc589065-2ad9-4d70-b24c-8747e82f5c50" />

**Historia y evolución del desarrollo web**  
  El desarrollo web comenzó en los años 90 con páginas estáticas en HTML. Con el tiempo, surgieron tecnologías como JavaScript, CSS y servidores dinámicos (PHP, ASP, etc.), permitiendo aplicaciones interactivas. Hoy existen frameworks modernos como React, Angular o Vue para frontend y Node.js, Django, Laravel para backend.
**Tipos de aplicaciones web**  
  - **Estáticas**: Solo muestran contenido fijo (HTML y CSS), sin interacción con el servidor.
  - **Dinámicas**: Generan contenido en tiempo real usando bases de datos y lenguajes de servidor (PHP, Python, etc.).
  - **SPA (Single Page Application)**: Aplicaciones web que cargan una sola página y actualizan el contenido dinámicamente (ej. usando React o Vue).
  - **PWA (Progressive Web App)**: Aplicaciones web que se comportan como apps nativas, permiten trabajar offline y utilizan tecnologías como Service Workers.

### Arquitectura de aplicaciones web
**Cliente-Servidor**  
  El navegador (cliente) solicita información al servidor, que responde con datos, páginas o servicios.
**Arquitectura de tres capas**  
  - Presentación: Interfaz que ve el usuario (HTML, CSS, JS).
  - Lógica: Procesa datos y gestiona reglas de negocio (backend).
  - Datos: Almacena información (bases de datos).
**REST y API-first design**  
  - **REST**: Estilo de arquitectura que usa HTTP para crear APIs escalables, usando métodos como GET, POST, PUT y DELETE.
  - **API-first design**: Es la estrategia de diseñar primero la API antes del desarrollo del frontend/backend, asegurando integración eficiente.

---

## 2. Tecnologías y Herramientas

### Lenguajes y tecnologías fundamentales
**HTML**: Lenguaje para estructurar páginas web.
**CSS**: Lenguaje para estilos visuales de la página.
**JavaScript**: Lenguaje de programación para dotar de interactividad al navegador.
**PHP**: Lenguaje de servidor ampliamente usado para desarrollo de backend.
**MySQL**: Sistema de gestión de bases de datos relacional, muy común en aplicaciones web.

### Control de versiones
**Git**: Herramienta de control de versiones para gestionar cambios en el código.
**GitHub**: Plataforma colaborativa basada en Git, permite compartir repositorios, revisar código y trabajar en equipo.
**Flujo de trabajo con ramas**  
  - **Branching**: Crear ramas para desarrollar nuevas funcionalidades sin afectar la rama principal.
  - **Merge**: Unir cambios de diferentes ramas.
  - **Pull Requests**: Solicitar la integración de cambios, permitiendo revisión y discusión antes de unir al proyecto principal.

---

## 3. Desarrollo Frontend y Backend

### Diseño e implementación del frontend
<img width="269" height="163" alt="image" src="https://github.com/user-attachments/assets/052186fb-66b1-4a85-8afb-5963f0ef93cf" />

**Maquetación/Wireframe/Mockup**  
  Herramientas como Figma, Adobe XD o papel y lápiz sirven para planificar la estructura visual antes de codificar.
**API**  
  El frontend consume datos de APIs (por ejemplo, usando fetch en JavaScript).

### Diseño e implementación del backend
**Servidor**  
  Software que responde a las peticiones del cliente (Node.js, PHP, Python).
**Manejo de peticiones y respuestas HTTP**  
  El backend recibe solicitudes HTTP (GET, POST, etc.) y responde con datos, páginas o mensajes.
**Conexión a bases de datos**  
  - **MySQL**: Relacional, más usado con PHP.
  - **PostgreSQL**: Relacional, más avanzado y potente.
  - **MongoDB**: No relacional, orientado a documentos, ideal para datos flexibles.

### Bases de datos
**Modelado de datos y relaciones**  
  Diseño de tablas, relaciones entre ellas (uno-a-muchos, muchos-a-muchos).
**ORM (Object Relational Mapping)**  
  Librerías que permiten manipular bases de datos usando objetos del lenguaje de programación (ej. Sequelize en Node.js, Eloquent en Laravel).
**CRUD desde el backend**  
  Implementación de operaciones Crear, Leer, Actualizar y Borrar desde la API.

### Seguridad básica en aplicaciones web
**Validación de formularios**  
  Comprobación de que los datos recibidos son correctos antes de procesarlos.
**Autenticación y autorización**  
  - **Autenticación**: Verificar identidad del usuario (login, registro).
  - **Autorización**: Permitir acceso a recursos según permisos del usuario.

---

## 4. Implementación, Integración y Despliegue

### Integración de frontend y backend
<img width="296" height="166" alt="image" src="https://github.com/user-attachments/assets/7fb161c9-2dd9-48fa-8a6e-5bb8b0069290" />

**Interfaz de usuario Frontend**  
  Desarrollo visual y funcional que interactúa con el usuario.
**Manejo de API**  
  Comunicación mediante HTTP entre frontend y backend.
**Proceso de Solicitud y Respuesta de Backend**  
  Flujo de información entre cliente y servidor.

### Almacenamiento en servidor
**Tipos de servidores**  
  - Compartidos, dedicados, VPS, serverless.
**Servidores y servicios de hosting**  
  Ejemplos: Heroku, Netlify, Vercel, AWS, DigitalOcean.
**Proveedores de servicios de almacenamiento**  
  Google Cloud Storage, Amazon S3, Azure Blob Storage.

### Optimización y rendimiento
**Optimización de recursos**  
  Minimizar imágenes, scripts y hojas de estilo para mejorar velocidad de carga.
**Despliegue de aplicaciones web**  
  Publicar la aplicación en internet, asegurando que sea accesible y funcional.
**CI/CD básico (Integración y entrega continua)**  
  Automatizar pruebas y despliegue usando herramientas como GitHub Actions, Jenkins, Travis CI.
**Documentación del proyecto**  
  Explicar cómo instalar, usar y mantener la aplicación (README, Wiki, comentarios en el código).
