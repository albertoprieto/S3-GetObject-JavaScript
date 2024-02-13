# Descargar Archivos desde Amazon S3

Este proyecto permite descargar archivos desde Amazon S3 utilizando JavaScript y la AWS SDK.

## Funcionalidades

- Descarga archivos en un rango especificado desde Amazon S3.
- Genera un archivo ZIP con los archivos descargados.
- Permite al usuario especificar el nombre del archivo ZIP.
- Valida los rangos de entrada para asegurarse de que sean válidos antes de la descarga.

## Variables de entorno
```bash
- export AWS_ACCESS_KEY_ID='tu_access_key_id'
- export AWS_SECRET_ACCESS_KEY='tu_secret_access_key'
- export AWS_REGION='tu_region'
```

## Cómo utilizar

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador web.
3. Ingresa el rango de archivos que deseas descargar y presiona el botón "Descargar Archivos".
4. Ingresa el nombre para el archivo ZIP cuando se te solicite.
5. El archivo ZIP se descargará automáticamente con los archivos solicitados.

## Requisitos

- Navegador web compatible con HTML5 y JavaScript.
- Credenciales válidas de AWS para acceder a los archivos en S3.

## Personalización

Si deseas personalizar el aspecto o la funcionalidad de la aplicación, puedes modificar el archivo `index.html` y el archivo `script.js` según tus necesidades.

## Tecnologías utilizadas

- HTML
- CSS (Bootstrap para estilos adicionales)
- JavaScript (AWS SDK para acceder a S3)
- JSZip para la generación de archivos ZIP

## Autor

Este proyecto fue desarrollado por [Jose Alberto Prieto](https://github.com/albertoprieto).

Si tienes alguna pregunta o sugerencia, no dudes en contactarme.

