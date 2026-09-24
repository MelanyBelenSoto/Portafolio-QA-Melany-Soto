# SQL-07 - JOIN

## Objetivo

Relacionar información de distintas tablas utilizando JOIN.

## Consulta 1 - Pedidos y clientes

SELECT *
FROM pedidos
INNER JOIN clientes
ON pedidos.IdCliente = clientes.IdCliente;


## Consulta 2 - Productos y categorías

SELECT *
FROM productos
INNER JOIN categorias
ON productos.IdCategoria = categorias.IdCategoria;


## Consulta 3 - Detalles de pedidos y productos

SELECT *
FROM detalles_pedidos
INNER JOIN productos
ON detalles_pedidos.IdProducto = productos.IdProducto;

## Resultado

Las consultas se ejecutaron correctamente y permitieron relacionar registros de diferentes tablas mediante campos en común

## Evidencias

### Consulta 1 - Pedidos y clientes

![Consulta 1 - Pedidos y clientes](../evidencias/SQL-07-JOIN/Captura%20de%20pantalla%202026-09-24%20174129.png)

### Consulta 2 - Productos y categorías

![Consulta 2 - Productos y categorías](../evidencias/SQL-07-JOIN/Captura%20de%20pantalla%202026-09-24%20174539.png)

### Consulta 3 - Detalles de pedidos y productos

![Consulta 3 - Detalles de pedidos y productos](../evidencias/SQL-07-JOIN/Captura%20de%20pantalla%202026-09-24%20174611.png)
