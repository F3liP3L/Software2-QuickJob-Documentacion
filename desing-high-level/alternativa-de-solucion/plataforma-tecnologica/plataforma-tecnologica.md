# 1.1.3.4 Plataforma Tecnologica

### Front End

Para el frontend del aplicativo se utilizara la libreria de Javascript **React**.

### Back End

Para el backend de los microservicios, se opto por usar el lenguaje Java version 20 conjunto con el framework Spring 

### Contenedor

Para los contenedores se utilizara docker. Herramienta que se integra muy bien con kub

### Manejador de Contenedores

Como gestor de contenedores se piensa usar Kubernetes, debido a su gran avanico de herramientas y compatibilidad, pero principalmente por su facilidad para administrador los contenedores y escalar horizontalmente, escalando segun la demanda de la aplicación.

### Bases de datos SQL

Para la bases de datos relacionales se piensa usar **MaridaDB** por su velocidad en las operaciones y el rendimiento que posee inclusive mayor a comparación de bases de datos con mucho perfomance como MySQL y SQL Server. Otra de las razones por la cual se piensa usar es por su consistencia y disponibilidad que tiene como base de datos relacional.

### Base de datos NO-SQL

Para las bases de datos no Relacionales se piensa hacer uso de **MongoDB** debido su facilidad de usO


### Blob Storage

Como Blob Storage se hara uso de **Azure Blob Storage**

### CDN

Como CDN se hara uso del **Azure CDN**

### WAF

Como WAF se hara uso de **Azure WAF**

### Api-Gateway

Como Api-Gateway se hara uso de **Azure Managament Gateway**

### Api Notificación

Para las notificaciones se utilizara **OneSignal** debido a que funciona tanto para el envio de notificaciones push como para el envio de correos electronicos y ofrece precios muy similares con su competencia especializada en solo uno de los dos servicios.

### Api Validacion de Documento de identificación

Para validar que la identidad de una persona si corresponde con la que se ingresa al momento del registro, se utilizara el **api de la registraduria nacional de colombia** que se encuentra integrada en un proovedor de servicios de apis **Apitude**.


### Identify Provider

Como provedor de identidades se hara uso de **Auth0** debido a sus herramientas, facilidad de uso y seguridad que brinda, además de aprovechar su capacidad para implementar MFA, atributo que resultara necesario para suplir escenarios de calidad relacionados con seguridad encontrados en los drivers arquitectonicos.



