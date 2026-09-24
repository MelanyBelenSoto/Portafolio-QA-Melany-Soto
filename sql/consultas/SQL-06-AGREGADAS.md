# SQL-06 - AGREGADAS

## Objetivo

Obtener valores calculados de los productos utilizando funciones agregadas de SQL.

## Consulta 1 - Precio promedio

SELECT ROUND(AVG(precio), 2) AS PrecioPromedio
FROM productos;


## Consulta 2 - Precio máximo

SELECT MAX(PrecioUnidad) AS PrecioMaximo
FROM productos;


## Consulta 3 - Precio mínimo

SELECT MIN(PrecioUnidad) AS PrecioMinimo
FROM productos;
`

## Resultado

Las consultas se ejecutaron correctamente y permitieron obtener el precio promedio, máximo y mínimo de los productos


## Evidencias

### Consulta 1 - Precio promedio

![Consulta 1 - Precio promedio](../evidencias/SQL-06-AGREGADAS/Captura%20de%20pantalla%202026-09-24%20171211.png)

### Consulta 2 - Precio máximo

![Consulta 2 - Precio máximo](../evidencias/SQL-06-AGREGADAS/Captura%20de%20pantalla%202026-09-24%20171235.png)

### Consulta 3 - Precio mínimo

![Consulta 3 - Precio mínimo](../evidencias/SQL-06-AGREGADAS/Captura%20de%20pantalla%202026-09-24%20171256.png)

