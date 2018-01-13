## Descripción general
El proyecto sirve como una plantilla base para el desarrollo de una aplicación web cotidiana , sistema de sesión de usuarios, middleware, generación de pdf.

## Proceso de instalación

1. Clonar el repositorio con el siguiente comando: ```git clone https://github.com/kroer84/bar.git```

2. Agarrar el archivo **.env.example** para poder crear el archivo **.env.** Configure lo siguiente: 
* DB_DATABASE
* DB_USERNAME
* DB_PASSWORD

3. Realice un ```composer update``` en la carpeta del proyecto
4. Genere la **APP_KEY** para el proyecto con el comando: ```php artisan key:generate```
5. Copie la llave en el archivo **.env**

## Roles de usuarios
El proyecto cuenta con dos tipos de usuarios:
* master
* admin
* user

## Configuración de Pdf
Ya se encuentra configurada la librería de dompdf junto con su controlador PdfController

## Barra de navegación
Barra de navegación validada para los 3 tipos de usuarios

## Configuración de Laravel Mix
Lista la preparación de Laravel Mix para poder juntar todos los js en uno solo al igual que los css.

## Recuperación de contraseñas 
Los usuarios serán capaces de recuperar sus contraseñas a través del correo electrónico.