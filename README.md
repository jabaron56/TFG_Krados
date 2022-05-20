## TFG-krados <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">

<img src="https://res.cloudinary.com/dpdob4mxw/image/upload/v1653067281/krados/banner_zkwfiu.svg">

Krados es un proyecto orientado a ofrecer una solución para las pequeñas empresas que necesitan digitalizarse.
Este proyecto incluye un **servicio REST** y una **aplicación Android** que servirá de ejemplo.


## Código fuente 📕

Aquí están los links de los repositorios en los que se han desarrollado tanto el servicio, como la aplicación:

 - 🔩 Repositorio con el codigo fuente del servicio REST: https://github.com/Lufram/TFG_Krados_webService
 - 📱 Repositorio con el codigo fuente de la aplicación Android:  https://github.com/Lufram/TFG_Krados_androidAPP 



***

## Tabla de contenido 🔖

- [Construido con](#construido-con) 🛠️
- [Instalación](#instalación) 📦
- [Autores](#autores) ✒️

***

### Construido con


### Herramientas 🔧

Una lista de las herramientas utilizadas en el proyecto:
* [Intellij IDEA](https://www.jetbrains.com/es-es/idea/) - El IDE utilizado para el desarrollo del servicio REST.
* [Android Studio](https://developer.android.com/?hl=es) - El IDE utilizado para el desarrollo de la aplicacion Android
* [Postman](https://www.postman.com/) - Cliente HTTP que nos da la posibilidad de hacer test.
* [XAMPP](https://www.apachefriends.org/es/index.html) - sistema de gestión de bases de datos MySQL, el servidor web Apache, PHP y Perl.

### Tecnologias ⚙️

Una lista de las tecnologías utilizadas en el proyecto:
* [Spring Boot](https://spring.io/projects/spring-boot) - El framework utilizado.
* [Maven](https://maven.apache.org/) - Manejador de dependencias

## Instalación
_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

_Software necesario para obtener una copia del proyecto el proyecto_

-Xampp  
-Intellij IDEA  
-Android Studio  
 
### Instalación y Despliegue 🔧

_Pasos a seguir_

1. _Lo primero es ejecutar el gestor XAMPP y arrancar apache y mysql._
2. _Después tendras que ingresar en la opción de admin de mysql disponible en el gestor XAMPP y crear la base de datos **krados_database**._
3. _Una vez creada la base de datos tendremos que dirigirnos al proyecto webService y ejecutar el servicio **KradosApplication** que se encuentra en la ruta **\src\main\java\com\edix\krados**._
4. _Ahora tendremos que dirigirnos al proyecto webService y ejecutar mediante Intellij las clases que se encuentran en la ruta **\src\test\java\com\edix\krados** en el siguiente orden:_
   - KradosApplicationRoles.
   - KradosApplicationCategory.
   - KradosApplicationProduct.
5. _Con las clases anteriormente mencionadas se llena la base de datos con unos datos de prueba._
6. _Ya tendriamos el servicio corriendo y la base de datos disponible, el siguiente paso sería ejecutar el proyecto de android mediante el emulador de Android Studio_  
Otra opción es instalar la apk que se encuentra en la carpeta de ejecutables de este repositorio en un dispositivo android físico y ejecutar a la vez el servicio REST en un servicio de hosting.

## Autores

* **Javier Barón Pérez** - (https://github.com/jabaron56)
* **Ismael De Gregorio López** - (https://github.com/Lufram)

