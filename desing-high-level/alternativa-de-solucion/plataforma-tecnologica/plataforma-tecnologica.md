# 1.1.3.4 Plataforma Tecnologica

### Front End

Para el frontend del aplicativo, se utilizará la librería de JavaScript **React** debido a sus diversas ventajas como lo es su rendimiento mejorado gracias a su enfoque de Virtual DOM, que permite actualizaciones eficientes y optimizadas en la interfaz de usuario. Esto se traduce en una mayor velocidad de respuesta y una experiencia de usuario más fluida, lo que garantiza en parte la usabilidad de la plataforma.
Además, React facilita la creación de Single-Page Applications (SPAs) debido a su estructura basada en componentes reutilizables. 

### Back End

Para el backend de los microservicios, se seleccionó **Java** en su versión 20 en colaboración con el framework **Spring Boot 3.0.6**. Spring Boot ofrece una configuración sencilla y una rápida capacidad de desarrollo. Con soporte para inyección de dependencias y una gestión efectiva de estas, cumple con los principios de mantenibilidad, modularidad y testabilidad. Además, se beneficia de la seguridad proporcionada por Spring Security y la biblioteca de pruebas JUnit.

### Contenedor

Para los contenedores se utilizara **Docker**, debido a su eficiencia de recursos, su amplia adopción y/o facilidad en su uso y su enorme comunidad activa, además de claramente su ecosistema y compatabilidad con otros recursos como el manejador de contenedores elegido en este caso kubernetes y su compatibilidad con otros sistemas operativos.

### Manejador de Contenedores

Como gestor de contenedores se piensa usar **Kubernetes**, debido a su gran avanico de herramientas y compatibilidad, pero principalmente por su facilidad para administrador los contenedores y escalar horizontalmente, escalando segun la demanda de la aplicación.

### Bases de datos SQL

Para la bases de datos relacionales se piensa usar **MaridaDB** por su velocidad en las operaciones y el rendimiento que posee inclusive mayor a comparación de bases de datos con mucho perfomance como MySQL y SQL Server. Otra de las razones por la cual se piensa usar es por su consistencia y disponibilidad que tiene como base de datos relacional.

### Base de datos NO-SQL

Para las bases de datos no Relacionales se piensa hacer uso de **MongoDB** principalmente por su gran escalabilidad horizontal ya que esta diseñado para manejar grandes volumenes de datos y altas cargas de trafico. Otras de las razones son su velocidad aprovechando los indices y su capacidad para realizar consultas complejas. Tambien se valoro su alta disponibilidad y su tolerancia a fallos.


### Blob Storage

Como Blob Storage se hara uso de **Azure Blob Storage** para el almacenamiento de datos en nuestra aplicación, esto se ha decidido utilizar debido a sus numerosas ventajas y capacidades, entre sus principales ventajas estas estan la escalabilidad y su capacidad para aumentar capacidad de almacenamiento automaticamente si lo ve necesario, su disponibilidad y durabilidad al replicar datos y garantizar proteccion contra perdida.

### CDN

Se implementara como CDN **Azure CDN** debido a que brinda una ventaja significativa en escalabilidad en comparación con otros servicios de CDN. Azure CDN tiene la capacidad de controlar y manejar de manera efectiva los picos de tráfico y las cargas elevadas de forma instantánea. Esto se traduce en una experiencia de usuario mejorada, ya que acelera la carga de la página y reduce la carga del servidor de origen, lo que garantiza un rendimiento constante incluso en situaciones de alto tráfico.

### WAF

Como WAF se hara uso de **Azure WAF** en nuestro proyecto debido a que nos brinda una capa adicional de seguridad para nuestra aplicación web. Con su protección contra ataques comunes como la inyección SQL, ataques XSS, entro otros,  reglas de seguridad personalizables, integración con servicios de Azure, escalabilidad y soporte continuo. 

### Api-Gateway

Como Api-Gateway se hará uso de **Azure Management Gateway** debido a su robustez, escalabilidad y amplias funcionalidades de gestión. Además, ofrece características avanzadas como autenticación, autorización y transformación de solicitudes, lo que nos permite construir y asegurar nuestra API de manera eficiente y confiable. Comparado con otros gateways, Azure Management Gateway se destaca por su escalabilidad global, su ecosistema de herramientas y servicios complementarios, conjunto con su enfoque en la seguridad y la gestión unificada de las APIs.

### Api Notificación

Para gestionar las notificaciones en la aplicación, hemos elegido utilizar OneSignal. Esta plataforma se destaca por su capacidad para enviar tanto notificaciones push como correos electrónicos, lo que la convierte en una solución integral para nuestras necesidades de notificación. A diferencia de otras soluciones especializadas que se enfocan únicamente en uno de los dos servicios. Otra de las desiciones del por que se uso es por su precio competitivo en comparación con otros provedores.

### Api Validacion de Documento de identificación

Para garantizar la validez de la identidad de los usuarios durante el proceso de registro, implementaremos la integración con el **API de la Registraduría Nacional de Colombia**, a través de un proveedor de servicios de APIs  Rest llamado **Apitude**. El API de la Registraduría Nacional de Colombia nos permitirá verificar si la identidad proporcionada por una persona durante el registro corresponde a la información oficial registrada en la entidad; garantizando que el usuario es una persona legal existente y garantizando una función critica de la aplicación.

### Api Validación de dispositivo

Para verificar que el dispositivo con el que se ingresa si sea el mismo que el del momento del registro de la aplicación se implementara el Api **Fingerprint** debido a que es de las apis de huellas de dispositivos más fuerte y con mejor documentación.

### Identify Provider

Como provedor de identidades se hara uso de **Auth0** debido a sus herramientas, facilidad de uso y seguridad que brinda, además de aprovechar su capacidad para implementar MFA, atributo que resultara necesario para suplir escenarios de calidad relacionados con seguridad encontrados en los drivers arquitectonicos.



