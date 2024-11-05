<!-- Tile -->
# Repositorio de aplicaciones FIORI
<!-- BODY -->
<p align="center"><img src="https://media.licdn.com/dms/image/v2/C561BAQGphD2B7YhWiQ/company-background_10000/company-background_10000/0/1585318850218/3afyc_cover?e=2147483647&v=beta&t=pFg6MYBqAQsHQJrKWw4HcPQCYJOToJm7ugtFourh44M"/></p> 

## Definición de directorios ✏️

### Seguir la nomenclatura según el proyecto asignado:

- INMOCAIXA-aplicación01
- COLONIAL-aplicación01
- LOYIC-BTP-aplicación01
- LOYIC-CATLOG-aplicación01

### Al realizar migraciones desde Web IDE, tener en cuenta las siguientes consideraciones para evitar conflictos y asegurar un proceso de migración más limpio y eficiente: 💡

- Verificar y eliminar controladores duplicados, conservando únicamente los que siguen la convención de nombre Name.controller.js (Cuando se compila, se regeneran en el /Dist)
- Revisar y corregir los caracteres HTML en los archivos i18n para garantizar que los textos se visualicen correctamente en la interfaz de usuario.
- Configura el archivo .gitignore para conservar los archivos de despliegue importantes, como los .yaml y .json. Omitir las dependencias innecesarias, archivos .zip, .mta, y la carpeta /dest.
  
<!-- FOOTER -->
---
**Always innovating** 🚀 By [LOYIC](https://www.loyic.com/) 💡
