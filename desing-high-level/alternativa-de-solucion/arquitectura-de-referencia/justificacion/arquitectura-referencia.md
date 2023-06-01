# 1.1.3.2.2 Explicacion Arquitectura de referencia

La arquitectura del proyecto que se va a utilizar es una arquitectura microservicios debido a que es la que mas ajustas con los drivers arquitectonicos encontrados, debido a que los atributos de calidad priorizados esta la mantenibilidad de la aplicación, rendimiento, escalabilidad y una gran disponibilidad.

## Componentes

### Front End

Es necesario tener un componente de Front End para cumplir con el atributo de calidad de usabilidad, ya que este encarga de implementar las diferentes interfaces de usuario (UI) coherentes e intuitivas que facilitan y estimulen la usabilidad de la aplicación.

### Back End

Es extremadamente necesario tener un componente de Back End separado del Front End, debido a que este se encargara de realizar todas las transacciones, comunicacion con sistemas externos, comandos y/o funciones que la aplicación ofrecera a los usuarios.

### Contenedor

Debido a la escalabilidad, eficiencia de recursos, seguridad, velocidad de respuesta, gestión y agilidad en el desarrollo y despliegue continuo, se usara un contenedor de aplicaciones.
### Manejador de Contenedores

Debido a la mantenibilidad, escalabilidad y disponibilidad se hara uso de un gestor de contenedores, de forma que permita automizar el despliegue y administrar los microservicios que estan en los contenedores. Cumpliendo a gran escala con la disponibilidad de la aplicación.

### Bases de datos SQL

Dentro de los microservicios de la aplicación se usaran bases de datos relacionales, con el fin de evitar la duplicidad de los registros y la integridad de ellos. Además esta base de datos SQL se utilizara para guardar datos que necesiten estar estructurados solidamente.

### Base de datos NO-SQL

Dentro de la aplicación va ser necesario hacer de bases de datos NO-SQL, debido a los grandes volumenes de datos que puede llegar a manejar un microservicio determinado. Tambien resultaria necesario usar estas bases de datos para suplir necesidad relacionadas con el rendimiento. 

### Blob Storage

Se utilizara un Blob Storage con el fin de almacenar en la nube todo el contenido estatico junto con el Front End de la aplicación.
### CDN

Este componente es necesario para cumplir con adecuadamente con el rendimiento de la aplicación, mejorando la entrega del contenido al usuario, minimizando la latencia y el performance.

### WAF

Este componente es necesario para asegurar parte de la seguridad de la aplicación al momento de hacer una petición a la api. Asegurando en gran medida que el trafico de la aplicación sea seguro antes de llegar al Back End.

### Api-Gateway

Este componente se encargara de gestionar, controlar y asegurar el acceso a múltiples APIs, asegurando de enrutar el llamado al microservicio correcto. Asegurando asi un monitoreo sobre las solicitudes y salidas realizadas y asi mismo garantizar rendimiento dando apoyo en la distribución cargas entre microservicios.

### Api Notificación

Este componente resulta extremedamente necesario puesto que la aplicación enviara notificaciones a los usuarios segun se cumplan determinadas transacciones, por tal motivo es necesario tener un componente externo de notificaciones que se encargue de enviar estos mensajes tanto por correo como por sms a los diferentes usuarios de la aplicación.

### Api Validacion de Documento de identificación

Este componente es de los más cruciales en la aplicación, puesto que sera necesario para validar que la identidad del usuario realmente corresponde a la ingresada y por lo tanto permitir solo un registro unico y veridico.

### Api Fingerprint Device

Este componente desempeña un papel fundamental en la verificación de que un usuario está accediendo a una aplicación desde el mismo dispositivo en el que se registró por primera vez. Su objetivo principal es fortalecer la seguridad y la autorización de la aplicación, al proporcionar una capa adicional de protección contra accesos no autorizados o suplantación de identidad.

### Identify Provider

Este componente sera necesario para cumplir con el atributo de calidad de seguridad, debido a que sera necesario utilizar un metodo de autorizacion para los usuarios de la aplicación; evitando asi vulnerabilidades y problemas de seguridad.

