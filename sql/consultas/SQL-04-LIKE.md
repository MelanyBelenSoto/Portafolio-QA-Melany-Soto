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


## Evidencias

### Consulta 1 - Ciudad comienza con B

![Consulta 1 - Ciudad comienza con B](../evidencias/SQL-04-LIKE/Captura%20de%20pantalla%202026-09-24%20163852.png)

### Consulta 2 - Ciudad contiene la letra a

![Consulta 2 - Ciudad contiene la letra a](../evidencias/SQL-04-LIKE/Captura%20de%20pantalla%202026-09-24%20163955.png)

### Consulta 3 - Ciudad termina con s

![Consulta 3 - Ciudad termina con s](../evidencias/SQL-04-LIKE/Captura%20de%20pantalla%202026-09-24%20164026.png)
