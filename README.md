Backend - README.md
# Green Bunny Store - Backend

## Descripción
Este es el backend de **Green Bunny Store**, desarrollado con **Spring Boot** para manejar la lógica del servidor, incluyendo la autenticación de usuarios, manejo de productos, carrito de compras y más.

## Tecnologías utilizadas
- **Spring Boot 3.5.6**
- **Spring Data JPA** (para interacción con MySQL)
- **Spring Security** (para autenticación y autorización)
- **MySQL 8**
- **Springdoc OpenAPI/Swagger** (para documentación de la API)
- **Mockito** para las pruebas unitarias del backend

## Instalación

1. Clona el repositorio del backend:

   ```bash
   git clone https://github.com/tu-usuario/green-bunny-backend.git
   cd green-bunny-backend


Instala las dependencias de Java:

mvn install


Ejecuta el backend:

mvn spring-boot:run


El backend estará disponible en http://localhost:8080/.

Documentación de la API

La documentación de la API está disponible a través de Swagger en la siguiente URL:

Swagger UI

Instrucciones de prueba

Para ejecutar las pruebas unitarias del backend:

mvn test


Esto ejecutará las pruebas unitarias con Mockito y Spring Boot.

Creación de la base de datos

Crear la base de datos en MySQL:

CREATE DATABASE tienda_virtual;


Configura las credenciales en el archivo application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/tienda_virtual?serverTimezone=UTC&useSSL=false
spring.datasource.username=usuario_proyecto
spring.datasource.password=1234
spring.jpa.hibernate.ddl-auto=update
springdoc.swagger-ui.path=/swagger-ui.html

Credenciales de prueba

Admin por defecto:

Email: admin@duocuc.cl

Contraseña: admin123

Rol: SUPER_ADMIN

Producción (orientación rápida)

Backend: empaquetar con mvn package y desplegar el JAR.

Configura proxy/reverse proxy para unificar dominios y evitar CORS.


---

