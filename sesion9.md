<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


## Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código:

```
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>

```

3. ### En el archivo CSS, agrega el siguiente código:

```
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}

```

4. ### Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

5. ### Practicar el uso de las propiedades de espaciado.

- Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

```
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

```

- ### Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

```
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

```

- ### Border: Agrega un borde de 5 píxeles de color rojo.

```
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

```

- ### Border-radius: Agrega un radio de esquina de 10 píxeles

```
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

```

- ### Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

```
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}

```

## Preguntas:

1. ### ¿Qué es la propiedad margin?
2. ### ¿Qué es la propiedad padding?
3. ### ¿Qué es la propiedad border?
4. ### ¿Qué es la propiedad border-radius?
5. ### ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

## SOLUCIÓN


1. ## ¿Qué es la propiedad margin?

La propiedad "margin" en el contexto del diseño web se utiliza para controlar el espacio en blanco alrededor de un elemento HTML, como un elemento de bloque (por ejemplo, un div) o un elemento de línea (por ejemplo, un párrafo). Esta propiedad afecta el espacio entre el borde del elemento y los elementos adyacentes.

La propiedad "margin" se puede definir de varias maneras, especificando diferentes valores para controlar el margen en los cuatro lados del elemento (superior, derecho, inferior e izquierdo). Aquí tienes un ejemplo de cómo se puede usar:

```
.elemento {
    margin-top: 10px;
    margin-right: 20px;
    margin-bottom: 10px;
    margin-left: 20px;
}

```

En el ejemplo anterior, se establecen márgenes diferentes para cada lado del elemento. También es posible especificar un solo valor para establecer márgenes iguales en todos los lados:

```
.elemento {
    margin: 10px;
}

```
La propiedad "margin" es útil para controlar la disposición de elementos en una página web y crear espaciado adecuado entre ellos. Puede ser especialmente útil en el diseño de diseños y páginas web responsivas.

2. ## ¿Qué es la propiedad padding?

La propiedad "padding" en el contexto del diseño web se utiliza para controlar el espacio entre el contenido de un elemento HTML y su borde. Es decir, afecta la separación entre el contenido del elemento y su borde. El "padding" se aplica a elementos de bloque y elementos de línea.

La propiedad "padding" se puede definir de varias maneras, especificando diferentes valores para controlar el relleno en los cuatro lados del elemento (superior, derecho, inferior e izquierdo). Aquí tienes un ejemplo de cómo se puede usar:

```
.elemento {
    padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 10px;
    padding-left: 20px;
}

```

En el ejemplo anterior, se establecen valores de relleno diferentes para cada lado del elemento. También es posible especificar un solo valor para establecer el mismo relleno en todos los lados:

```
.elemento {
    padding: 10px;
}

```
La propiedad "padding" es útil para controlar la apariencia y el espacio alrededor del contenido dentro de un elemento HTML, como divs, párrafos, encabezados, etc. Ayuda a separar el contenido del borde del elemento y es útil para lograr un diseño más limpio y estilizado en una página web.


3. ## ¿Qué es la propiedad border?

La propiedad "border" en el contexto del diseño web se utiliza para definir los bordes de un elemento HTML, como un div, una imagen o un párrafo. Esta propiedad controla la apariencia y estilo de los bordes del elemento, como su grosor, tipo de línea, color y radios de esquina (si se aplican). La propiedad "border" se puede dividir en varias subpropiedades para definir estos aspectos:

- border-width: Esta subpropiedad se utiliza para establecer el grosor del borde. Puedes definirlo en píxeles, ems, porcentajes u otras unidades de medida.

- border-style: Esta subpropiedad se utiliza para definir el tipo de línea del borde, como sólido, punteado, discontinuo, doble, entre otros.

- border-color: Esta subpropiedad se utiliza para establecer el color del borde. Puedes definirlo en una variedad de formatos de color, como nombres de colores, códigos hexadecimales o valores RGB.

- border-radius: Esta subpropiedad se utiliza para definir los radios de esquina del borde, lo que permite que los bordes tengan esquinas redondeadas en lugar de ser completamente cuadradas.

Aquí tienes un ejemplo de cómo se puede usar la propiedad "border" para aplicar un borde a un elemento HTML:

```
.elemento {
    border-width: 2px;
    border-style: solid;
    border-color: #333;
    border-radius: 5px;
}

```
En este ejemplo, se establece un borde de 2 píxeles de grosor con un estilo sólido de color gris (#333) y esquinas redondeadas con un radio de 5 píxeles.

La propiedad "border" es ampliamente utilizada en el diseño web para definir y personalizar la apariencia de los bordes de los elementos y contribuye a la estética y el diseño general de una página web.

4. ## ¿Qué es la propiedad border-radius?

La propiedad "border-radius" en el contexto del diseño web se utiliza para controlar el radio de las esquinas de un elemento HTML, lo que permite que los bordes tengan esquinas redondeadas en lugar de ser completamente cuadradas. Esto agrega un toque de suavidad y estilo a la apariencia de un elemento en una página web.

La propiedad "border-radius" se usa para establecer los radios de las esquinas de los elementos, como divs, imágenes o párrafos. Se pueden definir uno o varios valores para especificar los radios de las esquinas de diferentes maneras:

- Si se define un solo valor, se aplica a todas las esquinas, lo que da como resultado esquinas redondeadas idénticas.

```
.elemento {
    border-radius: 10px;
}

```
- Se pueden definir dos valores para especificar los radios de las esquinas horizontales y verticales por separado.

```
.elemento {
    border-radius: 10px 20px;
}

```
En este caso, las esquinas superiores izquierda y derecha tendrán un radio de 10 píxeles, mientras que las esquinas inferiores izquierda y derecha tendrán un radio de 20 píxeles.

Se pueden definir cuatro valores para especificar los radios de cada esquina en un orden específico (superior izquierda, superior derecha, inferior derecha, inferior izquierda).

```
.elemento {
    border-radius: 10px 20px 30px 40px;
}

```

En este ejemplo, se establecen radios diferentes para cada esquina del elemento.

La propiedad "border-radius" es útil para dar estilo y personalidad a los elementos de una página web y suavizar las esquinas para lograr un diseño más atractivo y amigable. Se usa comúnmente en combinación con otras propiedades CSS, como "border" y "background", para lograr el aspecto deseado.

5. ### ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

En las propiedades de espaciado, como "margin", "padding", y "border-width," puedes utilizar varias unidades de medida para definir valores. Algunas de las unidades de medida más comunes incluyen:

1. Píxeles (px): Esta es una unidad de medida fija que representa un píxel en la pantalla. Es comúnmente utilizada y proporciona una forma precisa de especificar el tamaño.

2. Em (em): El "em" es una unidad relativa que se basa en el tamaño de fuente actual del elemento padre. Un valor de 1em es igual al tamaño de fuente actual del elemento. Puedes utilizar "em" para definir el espaciado en relación con el tamaño de fuente.

3. Porcentaje (%): Las unidades de porcentaje se utilizan para especificar el espaciado en relación con el tamaño del elemento padre. Por ejemplo, puedes establecer un margen del 10% y eso será el 10% del ancho del elemento padre.

4. Centímetros (cm), milímetros (mm), y pulgadas (in): Estas unidades de medida son absolutas y se utilizan para definir el espaciado en términos de centímetros, milímetros o pulgadas. Son menos comunes en el diseño web, pero todavía se pueden utilizar.

5. Puntos (pt) y picas (pc): Estas son unidades de medida absolutas comúnmente utilizadas en impresión, pero a veces se emplean en el diseño web para tareas específicas.

6. Rem (root em): Similar a "em", pero en lugar de basarse en el tamaño de fuente del elemento padre, se basa en el tamaño de fuente del elemento raíz (normalmente el tamaño de fuente del elemento HTML).

7. Vh y vw: Estas unidades relativas se basan en el tamaño de la ventana del navegador. "1vh" es igual al 1% de la altura de la ventana, y "1vw" es igual al 1% del ancho de la ventana.

La elección de la unidad de medida dependerá de tus necesidades de diseño y del contexto de tu proyecto. Algunas unidades son más apropiadas que otras según la situación, por lo que es importante seleccionar la que mejor se ajuste a tus objetivos de diseño.

