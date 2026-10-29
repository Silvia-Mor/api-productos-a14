#### Operación

Para iniciar la aplicación, accedemos a la carpeta del proyecto y ejecutamos 'npm start'.

Para detener la aplicación, pulsamos Ctrl + C en el terminal donde está funcionando el servidor.

#### Comprobar el funcionamiento

Podemos comprobar que la API responde correctamente utilizando REST Client en VSC y enviando una petición a  http://localhost:3000/api/productos.

Si se produce un error, debemos revisar los mensajes que aparecen en el terminal.

#### Problemas habituales

| Problema                    | Comprobación                             | Posible solución                                 |
|-------------                | ------------                             | ----------------                                 |
| npm no está disponible      | Ejecutar npm --version                   | Instalar Node.js y npm                           |
| Faltan dependencias         | Revisar el mensaje de error del terminal | Ejecutar npm install en la carpeta del proyecto |   
| El puerto 3000 está ocupado | Comprobar qué proceso utiliza el puerto  | Liberar el puerto antes de iniciar la API        |