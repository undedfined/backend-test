# Back End skill-test

Hola y bienvenidx a esta prueba de habilidades, en esta ocasión mediremos tus habilidades como desarrolladorx Back End desarrollando una API REST para ser utilizada en una "tienda de tarjetas coleccionables".

![](https://data.whicdn.com/images/225715001/original.gif)

Los puntos que estaremos evaluando en esta prueba serán:

- Habilidad usando NodeJS
- Creatividad en el diseño de la REST API
- Documentación
    - Diagrama ER
    - Diagrama de base de datos
    - Documentación de API (swagger, postman, etc)
- Legibilidad del código
- Estructura del proyecto

## Descripción

En esta prueba estarás creando una API REST para una "tienda de tarjetas coleccionables", algo similar a una tienda en línea pero solo de un tipo de Item. Tendrás que diseñar y posteriormente desarrollar la funcionalidad necesaria para que la aplicación cumpla con las siguientes características:

- Registro y login de usuarios
- Usuario registra un nuevo item
- Usuario consulta items de otros usuarios (catálogo de tarjetas)
- Usuario consulta información de una tarjeta en específico
- Usuario consulta items propios (inventario)

##### A tomar en cuenta:

- Las acciones descritas anteriormente solo podrán ser ejecutadas por un usuario autenticado
- Las consultas a inventario y catálogo al menos deberán contar con un filtro opcional
- Para el registro de items el cuerpo de la petición deberá contar con una imagen codificada en formato base64 que posteriormente se guarde en la base de datos como una URI. (Puedes usar Cloud Storage de Firebase o similar)
- Puedes usar la base de datos de tu preferencia.
- Dockeriza el proyecto.

## Reglas

- Máximo de 2 días naturales para la entrega
- La aplicación deberá ser codificada usando las tecnologías descritas anteriormente (NodeJS)
- Puedes utilizar Express o Sails para la construcción del API REST
- El proyecto deberá entregarse en un repositorio con un manual de uso y ejecución

## Recomendaciones

- Has código legible y bien documentado!
- Sé lo más creativo posible!
- Desplegar a Heroku, Google Cloud o AWS suma puntos!

#### Buena suerte :) 
