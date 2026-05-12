Microservicios RESTful para gestion de catalogo. Java 21, Spring Boot, PostgreSQL, JWT.

Proceso login en postman: post http://localhost:8080/auth/login 
{
    "username": "admin@techstore",
    "password": "admin123"
}

Proceso post de producto raw JSOn
{
    "nombre": "Teclado Razer",
    "descripcion": "Teclado retroiluminacion",
    "precio": 23000,
    "stock": 23,
    "categoria": "PC",
    "activo": true
}