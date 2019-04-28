# Socket-Server :rocket:

Creando un backend utilizando TypeScript y Sockets.

Recontruir módulos de Node
```console
npm install
```

Generar el DIST
```console
tsc -w
```

Levantar Servidor, cualquiera de estos dos comandos
```console
nodemon dist/
node dist/
```


Este repositorio es impulsado por el curso de [Angular Aplicaciones en Tiempo Real](https://www.udemy.com/angular-aplicaciones-en-tiempo-real/).

## Detalles del Curso

### Sección 4, Clase 21
En esta sección 4, ya comenzaremos a trabajar con sockets, estos son parte de los temas que cubriremos:

- Configuración de socket.io en nuestro backend

- Implementar el patrón singleton en nuestra clase server

- Conectar Angular con nuestro servidor de sockets

- Detectar conexiones y desconexiones en el backend

- Detectar caídas y reconexiones del lado del cliente (Angular)

- Envío de nuestra primera comunicación por sockets

Crearemos la interfaz de usuario para enviar mensajes y mostrarle al usuario cuando hay conexión con el servidor y cuando la perdemos.

Empezaremos a construir una clase que podamos reutilizar fácilmente en un futuro, para no tener que configurar nada después, simplemente importar el servicio, configurar nuestro app.module y luego ya no hay que hacer nada más para trabajar con los sockets.

El código estará optimizado para facilitarnos la vida cuando trabajemos con sockets.
