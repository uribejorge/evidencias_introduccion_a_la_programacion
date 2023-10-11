<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


### Actividad: Propiedades de posicionamiento de CSS

#### Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

#### Instrucciones:

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, crea una estructura básica de página web con dos elementos div.
3. En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

Ejemplo:

```
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>

```

Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

Preguntas:

- ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
- ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
- ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

## SOLUCIÓN

# HTML
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="https://plantillashtmlgratis.com/" />
     <// link de Bootstrap
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <h1>CUADRO 1</h1>
    <div class="div1">
      <div class="div2"></div>
      <div class="div3"></div>
      <div class="div4"></div>
    </div>

    <// dejar este link siempre debajo para que pueda leer todos los archivos
    desde la pagina de Bootstrap.
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
      crossorigin="anonymous"
    ></script>
  </body>
</html>

```
# CSS

```
.div1 {
    background-color: rgb(130, 128, 223);
    height: 250px;
    width: 250px;
    position: browser;
    top: 250px;
    left: 2000px;
  }
  .div2 {
    background-color: rgb(227, 7, 7);
    height: 100px;
    width: 100px;
    position: relative;
    top: 70px;
    left: 20px;
    display: block;
  }
  .div3 {
    background-color: rgb(49, 21, 192);
    height: 100px;
    width: 100px;
    position: relative;
    top: 0px;
    left: 60px;
  }
  .div4 {
    background-color: yellow;
    height: 100px;
    width: 100px;
    position: relative;
    top: -80px;
    left: 100px;
    z-index: 3;
  }

```

1. ## ¿Cuál es la diferencia entre los valores position: absolute y position: relative?

Las propiedades CSS position: absolute y position: relative son utilizadas para controlar la posición de elementos en una página web, pero se comportan de manera diferente:

### position: absolute:

Cuando se aplica position: absolute a un elemento, este se posiciona en relación con el elemento padre más cercano que tenga una posición distinta a static. Si no hay ningún elemento padre con una posición diferente a static, entonces se tomará el elemento raíz del documento (generalmente el ``<html>).``
Las coordenadas de posición se especifican con las propiedades top, right, bottom y left. Puedes definir valores positivos o negativos para mover el elemento respecto a su posición normal en el flujo del documento.
Los elementos con position: absolute se desplazarán sobre otros elementos en la página, lo que significa que pueden superponerse a otros elementos.
La posición absoluta elimina el elemento del flujo normal de la página, lo que puede causar que otros elementos se colapsen o se superpongan en su lugar.

### position: relative:

Cuando se aplica position: relative a un elemento, este se posiciona en su ubicación normal en el flujo del documento, pero puedes ajustar su posición utilizando las propiedades top, right, bottom y left. El elemento se mueve en relación con su posición original.
La posición relativa no afecta la disposición de otros elementos en la página. Otros elementos no se ven afectados por la posición relativa del elemento.
Es útil para realizar ajustes de posición precisos sin perturbar el flujo normal del documento. Por ejemplo, puedes mover un elemento ligeramente hacia arriba o hacia abajo en relación con su posición original.
En resumen, position: absolute coloca un elemento en relación con un elemento padre posicionado o, si no lo encuentra, en relación con el elemento raíz, y elimina el elemento del flujo normal de la página, lo que puede causar superposiciones. En cambio, position: relative permite ajustar la posición de un elemento en relación con su posición original sin afectar la disposición de otros elementos en la página. Ambas propiedades son útiles en diferentes situaciones de diseño.


2. ## ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?

La propiedad z-index en CSS se utiliza para controlar el orden de apilamiento de elementos posicionados (elementos con una propiedad position diferente a static). Esto es útil cuando tienes elementos superpuestos en tu diseño y deseas determinar cuál debe estar delante de los demás.

El valor de z-index es un número entero, y los elementos con un valor de z-index más alto estarán en la parte superior de la pila y se superpondrán a elementos con valores más bajos o sin un valor de z-index. Aquí hay algunos conceptos clave para entender cómo se usa la propiedad z-index:

- El valor de z-index puede ser positivo, negativo o cero.

- Cuanto mayor sea el valor numérico de z-index, más arriba estará el elemento en la pila.

- Si dos elementos tienen valores de z-index, el elemento con el valor más alto estará en la parte superior.

- Si un elemento tiene un valor de z-index y otro no, el elemento con z-index estará en la parte superior.

#### Ejemplo de uso de z-index:

```
.elemento1 {
    position: relative;
    z-index: 2;
}

.elemento2 {
    position: relative;
    z-index: 1;
}

.elemento3 {
    position: relative;
    /* No se especifica z-index, por lo que se coloca debajo de los otros dos elementos. */
}

```

En este ejemplo, "elemento1" se colocará en la parte superior, seguido de "elemento2" y "elemento3". Los elementos con valores de z-index más altos se superponen a los que tienen valores más bajos o no tienen z-index especificado.

Es importante recordar que z-index solo tiene efecto en elementos que tienen una propiedad de posicionamiento diferente a static, como relative, absolute, o fixed. Además, en caso de empate entre elementos con el mismo z-index, el orden en el que aparecen en el código HTML determina su orden de apilamiento.


3. ## ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

La propiedad display en CSS se utiliza para controlar cómo se muestra un elemento en una página web al especificar su tipo de visualización. Esta propiedad afecta la forma en que el elemento se renderiza en relación con otros elementos y cómo ocupa espacio en el diseño. Aquí están algunos de los valores comunes de display y cómo se utilizan:

- display: block: Los elementos con esta propiedad se muestran como bloques de nivel y ocupan todo el ancho disponible. Normalmente, comienzan en una nueva línea y se extienden horizontalmente para llenar su contenedor padre.

- display: inline: Los elementos con esta propiedad se muestran en línea y ocupan solo el espacio necesario. No comienzan una nueva línea y se colocan junto a otros elementos en la misma línea.

- display: inline-block: Similar a inline, pero los elementos se comportan como bloques en el sentido de que puedes ajustar su ancho, alto, márgenes y relleno.

- display: none: Este valor oculta por completo el elemento y no ocupa espacio en el diseño. Puedes usar esto para esconder elementos de forma temporal.

- display: flex y display: grid: Estos valores se utilizan para establecer elementos como contenedores flexibles o de cuadrícula, lo que permite un control más avanzado del diseño y el posicionamiento de los elementos secundarios dentro de ellos.

- display: table, display: table-row, display: table-cell: Estos valores se utilizan para emular la estructura de una tabla HTML utilizando divs y otros elementos en lugar de elementos de tabla HTML.

- display: none: Este valor oculta completamente el elemento y no ocupa espacio en el diseño.

- display: initial: Restaura el valor de visualización predeterminado del elemento.

- display: inherit: Hereda el valor de visualización del elemento padre.

El valor de display es una herramienta esencial para controlar la disposición y presentación de elementos en una página web. Al elegir el valor adecuado, puedes lograr el diseño y el flujo visual deseados en tu sitio web.