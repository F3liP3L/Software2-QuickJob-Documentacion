# 1.2.4.1 Diagrama de Secuencia
El objetivo por el cual se creo este diagrama de secuencia es mostrar el orden y la forma en que un conjunto específico de componentes interactúa para llevar a cabo una transacción o caso de uso en particular; proporcionando un nivel de detalle adicional sobre cómo los componentes y objetos de la aplicación interactúan entre sí para completar un proceso. Estas son las diferentes secuencias de las transacciones que se realizan en el aplicativo.

## Secuencia de una transacción de actualización POST/PUT/DELETE

En el orden de la secuencia se ve como el Fronted entrega información al controller hace como puerta entrada principal y se encarga de revisar los datos que envio el usuario, los envia a una capa de facade donde se esta se encarga de servir como entrada al caso de uso de la otra capa de service y ya en la capa service se valida que cumpla con todas las reglas de negocio establecidas para que el repository pueda guardarlo en la base de datos.

![ds-actualizacion-post-put-delete](https://github.com/F3liP3L/Software2-QuickJob-Documentacion/blob/b0cf12f14b85f5eba3842153b46cbe7012713816/assets/vista-procesos/diagrama-secuencia/diagrama-secuencia-POST_PUT_DELETE.png)
## Secuencia de una transacción de consulta GET

En el orden de la secuencia para el caso de consulta es muy similar solo que no existe ninguna validación o regla de negocio a validar, además que en este caso si se retorna un dato que es un Json.

![ds-consulta-get](https://github.com/F3liP3L/Software2-QuickJob-Documentacion/blob/b0cf12f14b85f5eba3842153b46cbe7012713816/assets/vista-procesos/diagrama-secuencia/diagrama-secuencia-GET.png)
