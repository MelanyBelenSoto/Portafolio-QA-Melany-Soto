# SQL-10 - IS NULL

## Objetivo

Identificar registros que contienen valores nulos utilizando la condición IS NULL.

## Consulta 1 - Clientes sin región


SELECT *
FROM clientes
WHERE Region IS NULL;

## Consulta 2 - Empleados sin región

SELECT *
FROM empleados
WHERE Region IS NULL;


## Consulta 3 - Proveedores sin región

SELECT *
FROM proveedores
WHERE Region IS NULL;

## Resultado

Las consultas se ejecutaron correctamente y permitieron identificar registros que no tienen información almacenada en el campo Región

## Evidencias

### Consulta 1 - Clientes sin región

![Consulta 1 - Clientes sin región](../evidencias/SQL-10-IS-NULL/Captura%20de%20pantalla%202026-09-24%20181800.png)

### Consulta 2 - Empleados sin región

![Consulta 2 - Empleados sin región](../evidencias/SQL-10-IS-NULL/Captura%20de%20pantalla%202026-09-24%20181825.png)

### Consulta 3 - Proveedores sin región

![Consulta 3 - Proveedores sin región](../evidencias/SQL-10-IS-NULL/Captura%20de%20pantalla%202026-09-24%20181855.png)
