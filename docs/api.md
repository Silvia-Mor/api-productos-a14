<!--Qué hace cad endpoint y cómo probarlo con REST Client-->

### API de productos

#### Introducción

Esta API REST permite consultar los productos disponibles. Las peticiones se realizan mediante el método HTTP GET.

#### Endpoints disponibles

##### Obtener todos los productos

- Métodos - GET
- Ruta - /api/productos
- Descripción - Devuelve la lista completa de productos.
- Respuesta correcta - Código HTTP 200.

##### Obtener un producto por su identificación

- Método - GET
- Ruta - /api/productos/{id}
- Descripción - Devuelve el producto cuyo identificador coincide con el indicado.
- Respuesta correcta - Código HTTP 200
- Si no existe - Código HTTP 404 y mensaje Producto no encontrado.

#### Pruebas con REST Client

Las peticiones se pueden realizar desde VSC mediante la extensión REST Client, utilizando el archivo pruebas.http.

Para comprobar el funcionamiento de la API, se pueden realizar estas peticiones.

###
 GET http://localhost:3000/api/productos

###
 GET http://localhost:3000/api/productos/1

###
 GET http://localhost:3000/api/productos/99

La primera petición devuelve la lista de productos, la segunda devuelve el producto con identidicador 1 y la tercera permite comprobar la respuesta cuando el producto no existe.

