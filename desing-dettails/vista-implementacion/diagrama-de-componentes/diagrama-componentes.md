# 1.2.3.1 Diagrama de Componentes

Diagrama que indica la organización de los diversos componentes de Quickjob, además de sus respectivas dependencias lógicas y artefactos a usar.
Este diagrama cuenta con 7 capas, cada una encargada de su propia responsabilidad.

![Diagrama de Componentes](https://github.com/F3liP3L/Software2-QuickJob-Documentacion/blob/main/assets/vista-desarrollo/Diagrama-De-Componentes.png)

## Crosscutting

Componente que ofrece caracteristicas aspectuales que pueden ser utilizadas de forma general por cualquier proyecto construido en Java versión 20.

## QuickjobCrosscutting

Componente que ofrece caracteristicas aspectuales que pueden ser utilizadas por cualquier componentes de la aplicación Quickjob.

## QuickjobService

Componente encargado de garantizar el cumplimiento de toda la logica de negocio de la aplicación, asegurando que el dominio este protegido de accesos no autorizados.

## QuickjobDTO

Componente que ofrece los objetos de transferencia de datos con el fin de intercambiar datos entre el componente de API y el componente de Service.

## QuickjobEntity

Componente que tiene todas las entidades de acceso a datos que seran utilizadas por el componente de repositorio para llevar a cabo las operaciones de acceso a datos.

## QuickjobRepository

Componente que ofrece los mecanismos de acceso a datos del proyecto Quickjob.

## QuickJobApi

Componente encargado de publicar APIs relacionada con los servicios de negocio ofrecidos por la aplicación, cumpliendo su objetivo de permitir la comunicación entre Quickjob y otros sistemas.

