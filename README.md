Microservicios RESTful para gestion de catalogo. Java 21, Spring Boot, PostgreSQL, JWT.


Requisitos:
Java 21, Maven 3.9+, PostgreSQL 15 instalados.
base de datos `techstore` creada en PostgreSQL

Base de datos: `techstore`
Puerto: `5432`
usuario: `postgres`
contraseña: `admin123`


Proceso login en postman: post http://localhost:8080/auth/login 
{
    "username": "admin@techstore",
    "password": "admin123"
}

Proceso post de producto de ejemplo en formato Json
{
    "nombre": "Teclado Razer",
    "descripcion": "Teclado retroiluminacion",
    "precio": 23000,
    "stock": 23,
    "categoria": "PC",
    "activo": true
}