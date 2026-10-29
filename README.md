# API de productos - A1.4

Proyecto base para la práctica A1.4 de DAW. La aplicación ya está
desarrollada: su finalidad es servir de ejemplo para documentar
instalación, arquitectura, despliegue, operación y API.

## Ejecutar

``` bash
npm install
npm start
```

## Endpoints

-   `GET /api/productos`
-   `GET /api/productos/{id}`

## Pruebas

``` bash
curl http://localhost:3000/api/productos
curl http://localhost:3000/api/productos/1
curl http://localhost:3000/api/productos/99
```
<!-- Rest Client, esto es una extensión, permite probar una API desde el editor de VSC, no tengo que utilizar curl>
// Rest Client en vez de Swagger, aquí es 'pruebas.http' que es para hacer consultas.

// OpenAPI sirve para escribir formalmente la API mediante el archivo openapi.yaml

// En el apartado 3 hemos creado la estructura de docs/ y creado y rellenado mkdocs.yml

// Me he quedado en el apartado 4 del ejercicio. 