# Bienvenidos al curso de HTML Y CSS 

## Temas por ver 

* Clase de HTML su introducción 

### Equio de desarrollo

1. leogomezr23@gmail.com = admin
2. macstore27@gmail.com = colaborador 

## Temas principales 

* Que es HTML 
    * HyperText Markup Language 
    * Lenguaje de Marcas de Hipertexto 

## Estructura básica 
-> <html>
     <head>
        > En el [head] coloccamos información meta como puede ser información básica del sitio web tal como lenguaje, titulo, descripción y enlaces a hojas de estilos CSS
     </head>
     <body>
        > En el [body] colocamos todo lo que se verá en la página web, como imágenes, textos, videos y animaciones
     </body>
   </html>

# Explicaciones sobre Tags 

## Las tags van hacer de Planetas 

> Mercury = zona 1 asta las que sean necesarias 
  * La v0.0.1 = introducción 
  * La v0.0.2 = Textos

## Estos etiquetas <h></h>

* Las etiquetas h1 titulo - h2 subtitulo - h3 blogs o categorias 

## Preguntas de entrevistas para CSS

-- Que es la Especifidad en css
RES: Es como el navegador va a tomar ciertos valores en base 

# VALORES DE CSS Y VALORES 

> CUANDO LE DAMOS ESTILOS POR CLASES VALE 1 POR QUE ES MAYOR
  .CLASES{Aqui van las clases}
   IMPORT   ID   CLASS  ETIQUETA 
     0       0     1      0
> CUANDO LE DAMOS ID VALE 1 POR QUE ES MAYOR 
  IMPORT   ID   CLASS  ETIQUETA 
    0       1     0      0
> CUANDO LE DAMOS LA ETIQUETA VALE 1 POR QUE ES MAYOR 
   IMPORT   ID   CLASS  ETIQUETA 
    0       0     0      1
> CUANDO LE DAMOS LA EL !IMPORTANT VALE 1 POR QUE ES MAYOR 
   IMPORT   ID   CLASS  ETIQUETA 
    1       0     0      0

## BOX MODEL 

> En css Todo es una caja, pero como sea esa caja y que medidas tenga depende de 4 cosas

> La primera es el contenido, después de Padding (o relleno), Borde y finalmente el Margen

## DISPLAY 

* BLOCK 
  * Significa que un elemento se colocará por debajo del otro sin importar su tamaño o que tanto contenido tiene
* INLINE 
  * Significa que el elemento se posicionará a la derecha una vez que haya tomado el espacio que requiere.
* INLINE-BLOCK
  * El display inline-block permite darle un width, height, margin, a un elemento inline, lo que no es posible hacer en un elemento inline. 

## FLEXBOX 

### DISPLEY.FLEX
  > El flex pone los elemento de izquierda a derecha por default, osea pone row a todos los elementos, flex tiene varios elementos:

  1. flex-direction 
  2. align-items
  3. justing-content

  te voy a explicar cuando utilizarlos y cuando no.

** flex-direction: El flex-direction se utiliza cuando se va en columnas los elementos, por que en row ya estan definidos por defualt en el (display: flex), solo lo utilizamos en vertical.

** align-items: Lo utilizamos cuando tenemos una direccion en vertical osea en columna por que cuando tenemos row.

** justing-content: Esta opcion se hace cuando los elementos son en row o en linea, si los elementos estan en column no se aplicara ningun item de esta propiedad 

## GRID CSS

### Terminologia de grid 

* Algunas propiedades de CSS Grid son exclusivas cuando añades un displey:grid

* Para crear columnas utilizamos grid-template-columns
* Para crear rows o filas utilizamos grid-template-rows

* También es posible definir un diseño con grid-template-areas

> GRID LINES 


  1        2              4           5
  -------------------------------------
  |        |              |           | 
  |        |              |           |
  |        |              |           |
  |        |              |           |
  |        |              |           |
  |        |              |           |
  -------------------------------------

> GRID TRACK 
  
  ** HORIZONTAL 
  |-------------------------------------------|
  |                                           |
  |-------------------------------------------|

  ** VERTICAL 
  |--------------------------------------|
  |          |       |          |        |
  |          |       |          |        |
  |          |       |          |        |
  |--------------------------------------|

## UNIDADES 

> ABSOLUTAS 
  * Las unidades absolutas son las que son exactas, como pueden ser centímetros o pixeles.

> RELATIVAS 
  * Las unidades relativas toman su valor en base a otro elemento.
  
  Algunos ejemplos son: em, rem, vh, vw y porcentajes

## FORMAS DE ESCRIBIR CSS 

Existen diferentes formas de escribir código css: 
   1. Módulos
   2. BEM
   3. Utilidades
   4. SMACSS

> MÓDULOS
  EJEMPLO: Es coger la clase y añadirle una etiqueta 
    .card a {
      este son los módulos
    }
> UTILIDADES:Crear clases especificas a unos estilos.
    p-2{
      padding: 2rem; // 20pixeles
    }
   
> BEM - BLOCK ELEMENT MODIFIER 
  EJEMPLO: 
  > HTML 
     <DIV CLASS="CARD">
        <IMG 
        <H2>
  ** ACA TENEMOS UN HTML CON UN DIV Y DENTRO OTROS ELEMENTOS 

  > CSS ACA UTILIZAMOS BEM 
    .CARD{}
    .CARD__TITLE{}
    .CARD__IMG{}
  se identifica dentro del bloque se genera mas clases con un con dos guinoes abajos para identificarlos (__)

## CUANDO UTILIZAR FLEX O GRID 

### UTILIZAR FLEXBOS 

* Para la aliniación o distribución de los elementos que estarán dentro de contenedores.
 como Navbar cosas haci

### UTILIZAR CSS GRID 

* Para definir el Layout de tu sitio web, como pueden ser las columnas o contenedores de elementos para un diseño como las categorias es mejor css grid
