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

## Evidencias

### Consulta 1 - Clientes por país

![Consulta 1 - Clientes por país](../evidencias/SQL-08-GROUP-BY/Captura%20de%20pantalla%202026-09-24%20175616.png)

### Consulta 2 - Productos por categoría

![Consulta 2 - Productos por categoría](../evidencias/SQL-08-GROUP-BY/Captura%20de%20pantalla%202026-09-24%20175644.png)

### Consulta 3 - Pedidos por cliente

![Consulta 3 - Pedidos por cliente](../evidencias/SQL-08-GROUP-BY/Captura%20de%20pantalla%202026-09-24%20175716.png)
