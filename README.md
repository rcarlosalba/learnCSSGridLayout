# Aprendiendo CSS Grid Layout
Aputes de CSS Grid Layout

Es la apuesta de CSS3 para hace Layouts complejos. 
Se pueden hacer Layouts complejos, de muchas columnas y filas con diferentes tamaños.

## Grid container
Es el elmento padre, el que permitira manipular las vistas. 

## Grid Item
Lo que será el contenido dinámico. Son los hijos directos de Grid. 

## Grid Line
Las lineas internas y externas del grid

## Grid track
Espacio entre dos lineas adyacentes, filas y columnas

## Grid Cell

Espacio en dos filas adyacentes y dos columnas adyacentes. 

# Grid Area
Espacio rodeado por 4 grid lines

## Columnas en CSS Grid
Por defecto no hay asignación de filas y columnas
luego de colocar en el contenedor display:flex; podemos colocar grid-template-columns: anchoDeColumnas;

Acepta diferentes valores: 
px  %   fr  

## Filas en CSS Grid Layout
Por predeterminacion son 4 filas 

Por lo que si solo se colocan dos valores, los tomaran solo las primeras dos columnas. 

Eso es el Grid Explicito (lo definido por el usuario) y el implicito (lo que el sistema controla sin nosotros)

## Filas y columas
Siempre definiendo desde el contenedor
grid-template: filas / columas;

## Displays
Se puede hacer un grid dentro de otro grid. 
Una propuedad pendiente es subgrid en un display que herede los valores predefinidos.

## Espaciado entre los elementos


```
<html>

</html>

```