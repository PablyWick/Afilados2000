# Afilados2000

Rama principal del proyecto, donde se encuentra el código estable y listo para producción.


## Descripción

Afilados 2000 es un proyecto destinado a brindar soluciones de afilado de cuchillas de corte para la industria de la encuadernación. El proyecto busca abordar la problemática de la falta de visibilidad en línea y la necesidad de una gestión eficiente de relaciones con los clientes.

## Problema Identificado

La empresa Afilados 2000 carece de una presencia en línea y de una plataforma efectiva para captar clientes y gestionar relaciones con ellos. Esto limita su capacidad para atraer nuevos clientes y brindar un servicio de atención al cliente de calidad.

## Solución

La solución consiste en desarrollar una página web profesional y atractiva para Afilados 2000, promoverla en línea para aumentar su visibilidad y capacidades de captación de clientes, y establecer un sistema de gestión de relaciones con el cliente (CRM) para una atención al cliente eficiente.

## Arquitectura

La arquitectura del proyecto se basa en un enfoque monolítico, que incluye:

- Servidor de Aplicación: Aplicación Java basada en Spring Boot para la lógica de negocio.
- Servidor Web: Intermediario entre los clientes y el servidor de aplicaciones (Tomcat).
- Base de Datos: Almacenamiento de información de clientes y leads (SQL).
- Página Web y Recursos Estáticos: Contenido servido por el servidor web.
- CRM: Sistema de Gestión de Relaciones con el Cliente para la administración de leads y clientes.

## Tabla de Contenidos

- https://github.com/PablyWick/Afilados2000
- https://github.com/PablyWick/Afilados2000/blob/main/README.md

## Requerimientos

- Servidores de Aplicación y Web (como Tomcat o Jetty)
- Base de Datos (MySQL 8.0)
- Java Development Kit (JDK) 11
- Framework Spring Boot 2.5.3
- Paquetes adicionales detallados en el archivo `pom.xml` (Maven)
- Herramientas de Integración Continua (Travis CI)

## Instalación

### Ambiente de Desarrollo

- Instala el [JDK 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) y configúralo en tu sistema.
- Configura [Maven](https://maven.apache.org/download.cgi) como herramienta de construcción y administración de dependencias.

### Clonar el Repositorio

git clone - https://github.com/PablyWick/Afilados2000
cd Afilados2000

## Configuración de la Base de Datos.
Ajusta los detalles de la conexión a la base de datos en src/main/resources/application.properties.

## Ejecución de Pruebas Manualmente
Desde la raíz del proyecto, ejecuta las pruebas con Maven: mvn test

## Implementación en Ambiente Local
Asegúrate de configurar un ambiente de producción local adecuadamente.
Construye el proyecto: mvn clean install
Ejecuta el archivo JAR generado: java -jar target/tuprojecto.jar

## Implementación en Heroku
Crea una cuenta en Heroku.
Instala la Heroku CLI.
Desde la raíz del proyecto:
Inicia sesión en Heroku: heroku login
Crea una aplicación en Heroku: heroku create
Implementa la aplicación: git push heroku master

# Configuración

## Configuración del Producto
Edita los archivos de configuración según sea necesario, como src/main/resources/application.properties para ajustar la configuración de la base de datos y otras propiedades.

## Uso

### Usuario Final

Para obtener instrucciones detalladas sobre cómo utilizar Afilados 2000, por favor consulta nuestro Manual del Usuario.

### Usuario Administrador

Para administrar y configurar Afilados 2000, consulta la Guía del Administrador.

## Contribución

¡Gracias por tu interés en contribuir a Afilados 2000!

# Roadmap

## Futuras Implementaciones

Integración con redes sociales para ampliar la promoción en línea.
Análisis de métricas y ajustes para mejorar la experiencia del usuario.
Implementación de un sistema de pago en línea para pedidos de afilado.
Desarrollo de una aplicación móvil para facilitar la comunicación con los clientes.
