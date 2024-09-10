# Proyecto de JPA con Envers



## Introducción


Este proyecto es un ejemplo de cómo se puede implementar auditoría y versionamiento en una aplicación de bases de datos. El objetivo es registrar y rastrear todos los cambios realizados en la base de datos, para garantizar la integridad y transparencia de los datos.

## Características


*   **Auditoría**: se registra cada cambio realizado en la base de datos, incluyendo la fecha y hora del cambio, el usuario que realizó el cambio y los detalles del cambio.
*   **Versionamiento**: se mantiene un historial de versiones de cada registro en la base de datos, para que se pueda ver cómo ha cambiado el registro a lo largo del tiempo.

## Tecnologías utilizadas


*   **Java**: lenguaje de programación utilizado para desarrollar la aplicación.
*   **Hibernate**: framework de persistencia de datos utilizado para interactuar con la base de datos.
*   **Envers**: biblioteca de Java utilizada para implementar la auditoría y el versionamiento.

## Funcionamiento


1.  **Registro de cambios**: cuando se realiza un cambio en la base de datos, se registra el cambio en una tabla de auditoría.
2.  **Creación de versiones**: cuando se realiza un cambio en un registro, se crea una nueva versión del registro y se almacena en la base de datos.
3.  **Consulta de versiones**: se puede consultar el historial de versiones de un registro para ver cómo ha cambiado a lo largo del tiempo.

## Ventajas


*   **Integridad de los datos**: se garantiza la integridad de los datos al registrar y rastrear todos los cambios realizados.
*   **Transparencia**: se proporciona transparencia en la gestión de los datos, ya que se puede ver quién realizó cada cambio y cuándo.
*   **Seguridad**: se mejora la seguridad al mantener un historial de versiones de cada registro, lo que permite revertir cambios no deseados.

## Autor

**Fabio Escudero** - **Desarrollo de Software** - Comisión **3K10**