# SQL-09 - HAVING

## Objetivo

Filtrar grupos de registros después de aplicar GROUP BY utilizando la cláusula HAVING.

## Consulta 1 - Países con más de 3 clientes

SELECT Pais, COUNT(*) AS TotalClientes
FROM clientes
GROUP BY Pais
HAVING COUNT(*) > 3;

## Consulta 2 - Categorías con más de 5 productos

SELECT IdCategoria, COUNT(*) AS TotalProductos
FROM productos
GROUP BY IdCategoria
HAVING COUNT(*) > 5;

## Consulta 3 - Clientes con más de 10 pedidos

SELECT IdCliente, COUNT(*) AS TotalPedidos
FROM pedidos
GROUP BY IdCliente
HAVING COUNT(*) > 10;

## Resultado

Las consultas se ejecutaron correctamente y permitieron filtrar los grupos según la cantidad de registros obtenidos


## Evidencias

### Consulta 1 - Países con más de 3 clientes

![Consulta 1 - Países con más de 3 clientes](../evidencias/SQL-09-HAVING/Captura%20de%20pantalla%202026-09-24%20180359.png)

### Consulta 2 - Categorías con más de 5 productos

![Consulta 2 - Categorías con más de 5 productos](../evidencias/SQL-09-HAVING/Captura%20de%20pantalla%202026-09-24%20180509.png)

### Consulta 3 - Clientes con más de 10 pedidos

![Consulta 3 - Clientes con más de 10 pedidos](../evidencias/SQL-09-HAVING/Captura%20de%20pantalla%202026-09-24%20180529.png)
