# Aplicación de Carga de Camiones - Benayas

## Descripción

Se ha desarrollado una aplicación de **carga de camiones** para el cliente **Benayas**, cuyo objetivo es optimizar y mejorar la eficiencia del proceso de carga, garantizando que los pallets sean cargados en el orden correcto y de manera organizada dentro de cada camión.

La solución permite a los operarios gestionar y validar la carga en tiempo real, reduciendo errores operativos, mejorando la trazabilidad y agilizando las operaciones logísticas.

## Arquitectura de la Solución

La aplicación ha sido desarrollada utilizando **Microsoft Power Apps** y se integra con **Microsoft Dynamics 365 Business Central** mediante el uso de **tablas virtuales**, permitiendo el acceso y gestión de datos en tiempo real sin necesidad de replicar información.

### Flujo de Datos

1. La información logística y de expediciones se gestiona en **Dynamics 365 Business Central**.
2. Las **tablas virtuales** exponen los datos necesarios para la aplicación.
3. **Power Apps** consume los datos directamente desde Business Central en tiempo real.
4. Los operarios visualizan las órdenes de carga y los pallets asociados.
5. La aplicación valida el orden de carga de los pallets dentro del camión.
6. El estado de la carga se actualiza en tiempo real, permitiendo un seguimiento preciso del proceso.

## Tecnologías Utilizadas

* Microsoft Power Apps
* Microsoft Dynamics 365 Business Central
* Microsoft Dataverse Virtual Tables
* Microsoft Power Platform

## Funcionalidades Principales

* Consulta de cargas pendientes.
* Visualización de pallets asociados a cada expedición.
* Validación del orden correcto de carga.
* Actualización de estados en tiempo real.
* Control y seguimiento del proceso logístico.
* Reducción de errores durante la carga de camiones.

## Beneficios de la Solución

* Mayor eficiencia en las operaciones de carga.
* Optimización de los tiempos de preparación y expedición.
* Acceso a información en tiempo real.
* Eliminación de duplicidad de datos.
* Mayor control y trazabilidad de los pallets cargados.
* Integración nativa con Business Central.

## Dependencias

* Entorno de Microsoft Power Platform configurado.
* Instancia de Microsoft Dynamics 365 Business Central.
* Configuración de tablas virtuales entre Business Central y Dataverse.
* Permisos adecuados para usuarios operativos y administradores.

## Consideraciones

* La disponibilidad de los datos depende de la correcta configuración de las tablas virtuales.
* Cualquier modificación en las tablas o procesos de Business Central debe ser evaluada para garantizar la compatibilidad con la aplicación.
* Se recomienda monitorizar el rendimiento y la conectividad de las tablas virtuales para asegurar la disponibilidad de la información en tiempo real.

## Cliente

**Benayas**

Desarrollo realizado en Microsoft Power Apps con integración en tiempo real a Dynamics 365 Business Central mediante tablas virtuales.
