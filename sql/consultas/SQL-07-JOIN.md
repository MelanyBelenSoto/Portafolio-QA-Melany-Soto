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
