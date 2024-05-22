
-Desafío Back End - API REST con Spring-

¡Bienvenido al reto de desarrollo del Desafío Back End!

-En este desafío, se te pide crear un API REST utilizando Spring para un foro.

Funcionalidades:

Crear un nuevo tema:
La API debe permitir a los usuarios registrar nuevos temas mediante solicitudes POST a /temas.
La información del tema (título, mensaje, autor y curso) debe enviarse en formato JSON en el cuerpo de la solicitud.


Reglas del negocio:

Todos los campos son obligatorios.
No se permiten temas duplicados (con el mismo título y mensaje).


Mostrar todos los temas creados:

La API debe proporcionar un endpoint para listar todos los temas mediante solicitudes GET a /temas.
Los datos del tema (título, mensaje, fecha de creación, estado, autor y curso) se devolverán en formato JSON en la respuesta.



Mostrar un tema específico:

La API debe tener un endpoint para mostrar un tema específico mediante solicitudes GET a /temas/{id}.
Los datos del tema se devolverán en formato JSON en la respuesta.


Actualizar un tema:

La API debe permitir a los usuarios actualizar temas mediante solicitudes PUT a /temas/{id}.
Se aplicarán las mismas reglas de negocio que para la creación de un tema.


Eliminar un tema:

La API debe proporcionar un endpoint para eliminar temas mediante solicitudes DELETE a /temas/{id}.


Tecnologías:

Java 17
Spring Boot 3
Base de datos para la persistencia de la información
Flyway para la migración de la base de datos