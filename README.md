# generarPdf
## Carpeta generatePdf --> Frontend :man_technologist:
```
En esta carpeta esta todo el proyecto de la parte front, llamada y consumo de los servicos REST API, en ella se crea 
un CRUD básico de un usuario, con su listado de tabla. Para ello hemos utilizado la libreria primevue y primeicons.
```

## Project setup FRONT
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Carpeta generatePDF --> Backend :man_technologist:
```
En esta carpeta esta todoel proyecto de la parte backend, cración del model usuario, creación de los servicios y los 
controladores de las peticiones Http. He creado un CRUD básico con un servicio más, llamado PdfServie,en el cúal genera
un pdf de los datos del usuario id que le pasamos.
Para ello hemos utlizado librerias: jtidy, thymeleaf-layout-dialect, spring-boot-starter-thymeleaf y openpdf
```

## Project setup BACK
```
Es necesario tener una base de datos mysql llamada pruebas que este en abierta en el puerto 3306.
Si vas a utilizar otra base de datos, tienes que ir a: generatePDF/src/main/resources/application.properties, y aquí, cambiar los datos necesarios.
Una vez tengas vinculada tu base de datos podras ejecutar el proyecto sin errores.
```

## Muchas gracias por ver mi proyecto :grin:
