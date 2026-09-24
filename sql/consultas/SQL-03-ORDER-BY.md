# SQL-03 - ORDER BY

## Objetivo

Ordenar los registros de la tabla clientes utilizando diferentes criterios de ordenamiento.

## Consulta 1 - Ciudad ascendente

sql
SELECT * 
FROM clientes
ORDER BY Ciudad ASC;


Consulta 2 - Ciudad descendente

sql
SELECT * 
FROM clientes
ORDER BY Ciudad DESC;


## Consulta 3 - País y ciudad

sql
SELECT * 
FROM clientes
ORDER BY Pais ASC, Ciudad ASC;


## Resultado

Las consultas se ejecutaron correctamente y los registros se mostraron ordenados según los criterios indicados.


## Evidencias

### Consulta 1 - Ciudad ascendente

![Consulta 1 - Ciudad ascendente](../evidencias/SQL-03-ORDER-BY/Captura%20de%20pantalla%202026-09-24%20161653.png)

### Consulta 2 - Ciudad descendente

![Consulta 2 - Ciudad descendente](../evidencias/SQL-03-ORDER-BY/Captura%20de%20pantalla%202026-09-24%20161746.png)

### Consulta 3 - País y ciudad

![Consulta 3 - País y ciudad](../evidencias/SQL-03-ORDER-BY/Captura%20de%20pantalla%202026-09-24%20161830.png)

