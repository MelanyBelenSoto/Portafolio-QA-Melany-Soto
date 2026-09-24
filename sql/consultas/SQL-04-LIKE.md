# SQL-04 - LIKE

## Objetivo

Buscar registros que coincidan con determinados patrones de texto utilizando el operador LIKE.

## Consulta 1 - Ciudad comienza con B


SELECT * FROM clientes
WHERE Ciudad LIKE 'B%';


## Consulta 2 - Ciudad contiene la letra a

SELECT * FROM clientes
WHERE Ciudad LIKE '%a%';


## Consulta 3 - Ciudad termina con s

SELECT * FROM clientes
WHERE Ciudad LIKE '%s';

## Resultado

Las consultas se ejecutaron correctamente y permitieron filtrar los registros según diferentes patrones de texto utilizando LIKE
