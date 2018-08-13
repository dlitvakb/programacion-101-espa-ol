# Tipos de datos

La mayor parte de las tareas de un programa de computadora son la interpretación y la transformación de los datos.
Hay diferentes tipos de datos, como pueden ser los numéricos, textuales u otros mas complejos.

## Tipos numericos

En los tipos numéricos, hay 2 familias que son las más importantes, los numeros enteros y los de punto flotante.

### Enteros

Los enteros son todos los números que se pueden representar con solo la parte entera, por ejemplo: `1`, `2`, `3`, `12376823` o `-5432`.
Dependiendo el lenguaje de programación, dichos números pueden tener un límite inferior o superior; en el caso de Ruby,
los números enteros no tienen límites, pudiendo representar todos.

Este tipo de dato en Ruby se llama `Integer`.

### Punto Flotante

Los números de punto flotante son todos aquellos que se pueden representar con una parte decimal, por ejemplo: `0.1`, `123.456`, `-57.0001`.
Nuevamente, dependiendo el lenguage de programación, dichos numeros pueden estar limitados; en el caso de Ruby,
los números de punto flotante no tienen límites.

Este tipo de dato en Ruby se llama `Float`.

### Cadenas de Texto

Las cadenas de texto son cualquier fragmento de texto de 0 o más caracteres. Se representan rodeados entre comillas simples (`'`) o
comillas dobles (`"`), por ejemplo: `'Hola Mundo!'` o `"Como estás?"`.

En Ruby, la desición entre cual tipo de comillas utilizar, depende de 2 factores:

1. La aparición de comillas simples o dobles dentro del texto a representar.
En tal caso se usa la que mas conveniente sea para evitar tener que utilizar secuencias de escape, como: `\"`.

2. La necesidad de interpolar dinámicamente contenido en una cadena.
En este caso solo la comilla doble nos permite realizar dicha operación.
La interpolación la explicaremos en un ejercicio próximo.

Este tipo de dato en Ruby se llama `String`.

### Valores de verdad o Booleanos

Los valores de verdad, mas comunmente llamados *Booleanos* en programación, son los valores para verdadero y falso.
En Ruby se representan con `true` y `false`.

### Listas

Una lista es una colección ordenada de 0 o más elementos. En el caso de Ruby, los elementos incluídos en la colección
pueden ser de cualquier tipo, pero es recomendado evitar esto y por lo general mantener las listas "puras",
dado que es mucho mas sencillo operar sobre una lista donde todos los elementos son homogéneos.

Este tipo de dato en Ruby se llama `Array`.

### Diccionarios

Similares a las listas, los diccionarios son colecciones de 0 o más elementos que están indexadas por claves.
A diferencia de las listas, no hay recomendación particular sobre la "pureza" de esta estructura de datos,
dado que se accede a sus contenidos mayormente a través de sus claves, en lugar de secuencialmente.

Este tipo de dato en Ruby se llama `Hash`.

### Otros tipos de datos

En Ruby, los tipos mencionados anteriormente no son los únicos existentes, sin embargo,
estos son los más básicos y frecuentemente utilizados.

Dicho ésto, uno puede crear sus propios tipos de datos, y veremos como hacerlo en el módulo de *Clases*.
Donde vamos a ver como componer los tipos de datos que aprendimos en esta lección y otros tipos de datos
para generar estructuras mas complejas.
