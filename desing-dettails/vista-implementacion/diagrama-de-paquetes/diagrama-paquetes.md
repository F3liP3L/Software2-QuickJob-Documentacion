# 1.2.3.2.1 Diagrama de Paquetes Backend

Diagrama que representa e indica a nivel logico la estructura de los diferentes paquete que contiene la aplicación y a su vez muestra las dependencias y/o relaciones que hay entre ellos. De forma que sirva de guia detallada para construir los diferentes paquetes de la aplicación Quickjob.

![Diagrama-de-Paquetes-Backend](https://github.com/F3liP3L/Software2-QuickJob-Documentacion/blob/main/assets/vista-desarrollo/Diagrama-de-Paquetes-Backend.png)

A grandes rasgos se puede apreciar como cada paquete de back-end interactúa con otros paquetes, como todos se comunican con el crosscutting y como muchos poseen un paquete **\<\<domain\>\>** que indica que por cada objeto del dominio existe un determinado paquete.
# 1.2.3.2.2 Diagrama de Paquetes Fronted

Representa la estructura de los diferentes paquetes que contiene el front-end de la aplicación. Esto con el objetivo de crear una guía detallada de como construir toda la estructura de directorios que poseerá el Front-end del aplicativo. A grandes rasgos se observa como casi todos los paquetes interactúan con el paquete util, también como service y components se comunican con config para obtener sus configuraciones o constantes creadas y como components usa el paquete de redux con el fin de importar los estados.


![Diagrama-de-Paquetes-Frontend](https://github.com/F3liP3L/Software2-QuickJob-Documentacion/blob/main/assets/vista-desarrollo/Diagrama-de-Paquetes-Frontend.png)



