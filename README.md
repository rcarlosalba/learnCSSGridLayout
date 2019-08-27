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
Columnas: grid-column-gap: valor;
Filas: grid-row-gap: valor;
ambos: grid-gap: valor;

## Unidades de Medida 
Se agrega fr (fraccion) 
Se puede utilizar el valor repeat
repeat (4, 1fr)
se pueden establecer minimo y maximos
repeat(4,(minmax(200px, 1fr))

## Areas de Contenido
se declaran por medio de 
grid-template-areas: nombres de las areas separados por comillas
se invocan en las clases con grid area

## Modificando altos y anchos
en el caso de las filas 
grid-column-start: fila en la que inicia;
grid-column-end: fila en la que termina;
forma resumida
grid-column: 2 / span 2; le decimos que ocupe dos valores es cuando ignoranmos cuanto es el ancho de nuestro grid, mantiene mas dinamico y congruente el diseño
grid-column: 2 / 4;

aplica de igual forma a las columnas
grid-column: 2 / 4;

en conjunto se ve asi: 

grid-column:4 / span 2;
grid-row: 5 / span 2;


```
<html>

</html>

```