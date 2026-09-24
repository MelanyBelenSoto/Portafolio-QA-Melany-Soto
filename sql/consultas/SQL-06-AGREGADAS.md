# SQL-06 - AGREGADAS

## Objetivo

Obtener valores calculados de los productos utilizando funciones agregadas de SQL.

## Consulta 1 - Precio promedio

SELECT AVG(PrecioUnidad) AS PrecioPromedio
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
