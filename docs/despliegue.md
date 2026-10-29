<!-- Pasos para pasar del código fuente a tener la API funcionando.-->

### Despligue

#### Preparación del proyecto

Antes de iniciar la aplicación, debemos comprobar que Node.js y npm están instalados y que disponemos de los archivos del proyecto.

#### Instalación de dependencias

Desde el terminal, accedemos a la carpeta api-productos-a14 y ejecutamos 'npm install'.
Este comando instala las dependencias necesarias para ejecutar la aplicación, incluido Express.

#### Inicio de la aplicación

Para iniciar la API, ejecutamos 'npm start' desde la carpeta del proyecto.
Si el servidor se inicia correctamente, aparecerá un mensaje indicando que la API está disponible en http://localhost:3000

#### Comprobación y seguridad

Para comprobar que el despligue funciona, accedemos a  http://localhost:3000/api/productos y verificamos que se muestra la lista de productos.

Antes de publicar el proyecto, debemos comprobar:

- No incluir contraseñas ni otros datos secretos en el repositorio.
- Añadir los archivos que contengan información sensible a .gitignore.
- Utilizar HTTPS en un entorno de producción.
- Exponer únicamente los puertos necesarios.

