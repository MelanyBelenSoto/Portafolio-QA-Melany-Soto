# SQL-08 - GROUP BY

## Objetivo

Agrupar registros que tienen valores en común y obtener la cantidad de registros de cada grupo.

## Consulta 1 - Clientes por país

SELECT Pais, COUNT(*) AS TotalClientes
FROM clientes
GROUP BY Pais;


## Consulta 2 - Productos por categoría

SELECT IdCategoria, COUNT(*) AS TotalProductos
FROM productos
GROUP BY IdCategoria;


## Consulta 3 - Pedidos por cliente

SELECT IdCliente, COUNT(*) AS TotalPedidos
FROM pedidos
GROUP BY IdCliente;


## Resultado

Las consultas se ejecutaron correctamente y permitieron agrupar los registros según diferentes campos.
