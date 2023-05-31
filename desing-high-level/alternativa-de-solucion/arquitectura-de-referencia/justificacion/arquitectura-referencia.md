# 1.1.3.2.2 Explicacion Arquitectura de referencia

La arquitectura del proyecto que se va a utilizar es una arquitectura microservicios debido a que es la que mas ajustas con los drivers arquitectonicos encontrados, debido a que se priorizo la mantenibilidad de la aplicación, escalabilidad y una gran disponibilidad.

## Componentes

### Front End

Es necesario tener un componente de Front End para cumplir con el atributo de calidad de usabilidad, ya que este encarga de implementar las diferentes interfaces de usuario (UI) coherentes e intuitivas que facilitan y estimulen al uso de la aplicación.

### Back End

Es extremadamente necesario tener un componente de Back End separado del Front End, debido a que este se encargara de realizar todas las transacciones, comunicacion con sistemas externos, comandos y/o funciones que la aplicación ofrecera a los usuarios.

### Contenedor

Debido a la escalabilidad, eficiencia de recursos, seguridad, velocidad de respuesta, gestión y agilidad en el desarrollo y despliegue continuo, se usara un contenedor de aplicaciones.
### Manejador de Contenedores

Como gestor de contenedores se piensa usar Kubernetes, debido a su 
### Bases de datos SQL

Dentro de los microservicios de la aplicación se usaran bases de datos relacionales, con el fin de evitar la duplicidad de los registros y la integridad de ellos. Además esta base de datos SQL se utilizara para guardar datos que necesiten estar estructurados solidamente.

### Base de datos NO-SQL

Dentro de la aplicación va ser necesario hacer de bases de datos NO-SQL, debido a los grandes volumenes de datos que puede llegar a manejar un microservicio determinado. Tambien resultaria necesario usar estas bases de datos para suplir necesidad relacionadas con el rendimiento. 


### Blob Storage

Se utilizara un Blob Storage con el fin de almacenar en la nube todo el contenido estatico, Front End de la aplicación.
### CDN


### WAF


### Api-Gateway

### Api Notificación

Este componente resulta extremedamente necesario puesto que la aplicación enviara notificaciones a los usuarios segun se cumplan determinadas transacciones, por tal motivo es necesario tener un componente externo de notificaciones que se encargue de enviar estos mensajes tanto por correo como por sms a los diferentes usuarios de la aplicación.

### Api Validacion de Documento de identificación

Este componente es de los más cruciales en la aplicación, puesto que sera necesario para validar que la identidad del usuario realmente corresponde a la ingresada.

### Identify Provider

