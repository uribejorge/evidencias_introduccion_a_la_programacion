<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


## Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado ``<header>``
- Tres párrafos ``<p>``
- Una imagen ``<img>``
- Un pie de página ``<footer>``

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados ``<h1>``
- Color azul a los párrafos ``<p>``
- Borde grueso negro a la imagen ``<img>``

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un ``<div>``
- Centrar el contenido de la sección ``<section>``

## SOLUCIÓN

### INDEX.HTML

```
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="Styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<header>
    <h1>Desarrollador de software</h1>

</header>
<div class="contenedor" id="sombras"><img
        src="https://n9.cl/6di4l"
        alt="">
</div>
<section>
    <p class="destacado">Un desarrollador es un programador o una compañía comercial que se dedica a uno o más aspectos
        del
        proceso de desarrollo de software. Se trata de un ámbito más amplio de la programación algorítmica.

        En informática, un desarrollador1​ (al que con frecuencia también se conoce como analista-programador), es un
        especialista en informática que es capaz de concebir y elaborar sistemas informáticos (paquetes de software),
        así
        como de implementarlos y ponerlos a punto, utilizando uno o varios lenguajes de programación.

        El desarrollador puede contribuir a la visión general del proyecto más a nivel de aplicación que a nivel de
        componentes, así como en las tareas de programación individuales.

        Conforme pasa el tiempo, la separación entre el diseño de sistemas informáticos, el desarrollo de software, y la
        programación, se van haciendo más claras y diferenciadas. En el mercado laboral suele encontrarse una
        diferenciación
        entre programadores y desarrolladores, siendo estos últimos los que diseñan la estructura o jerarquía de clases.
        Incluso esos desarrolladores se convierten en arquitectos de sistemas informáticos, o sea, aquellos que diseñan
        la
        arquitectura a varios niveles o las interacciones entre componentes de un proyecto de software grande.
    </p>
    <p class="grande">
        El concepto de desarrollo de software incluye:

        Trabajo en equipo: los proyectos son en general una colaboración entre varios desarrolladores, que tratan cada
        uno
        una parte específica del sistema que se desarrolla, y también de otros tipos de colaboradores, como los
        comerciales
        (que definen con el cliente la finalidad y las necesidades del producto), o como los diseñadores gráficos (que
        definen el aspecto de las pantallas y cuestiones relativas a la ergonomía), etc.
        Concepción o diseño: a partir de un pliego de condiciones (user requirement specifications), se definen las
        especificaciones técnicas (estructura de datos, comunicación entre módulos, etcétera).
        Pruebas: sirven para detectar las disconformidades de trabajadores y clientes, y los errores.
        Mantenimiento: abarca la corrección de los errores después de que comience el uso comercial del programa
        informático, así como las mejoras que se revelen como necesarias para hacer evolucionar el producto.
        Nota: para que un programador se convierta en desarrollador, debe poseer experiencia y saber el manejo y la
        aplicación de metodologías de desarrollo; es sobre todo la experiencia y el conocimiento técnico, lo que ha
        impulsado la evolución del término 'programador' hacia el término 'desarrollador'.

    </p>
    <p id="principal">
        Tareas específicas de un desarrollador
        Para responder adecuadamente y en la mejor forma a las necesidades del cliente, conviene que en una primera
        etapa el
        desarrollador establezca un pliego de condiciones, a efectos de determinar y especificar las necesidades del
        cliente
        en materia de automatización, informatización, y control, asunto por asunto. En esta etapa, conviene que se
        aclaren
        las siguientes cuestiones:

        En cuanto a la informatización, convendrá aclarar las ventajas de la misma, ya que hay casos en los que las
        cosas
        pueden llegar a ser más eficientes y con mejores resultados económicos sin informatización que con ella. Esta
        cuestión es crucial y fundamental, y deberá ser analizada con visión de largo alcance, pues de lo que
        generalmente
        se trata, es de concebir un sistema informático que acompañe al cliente en su evolución futura durante los
        próximos
        años.
        Esta es una fase crucial puesto que no solo se debe responder a las necesidades actuales del cliente, sino
        también
        diseñar un sistema informático que acompañará al cliente en la evolución de sus actividades.

        En una segunda etapa se desarrolla una solución técnica (hardware) y se crea un modelo (análisis orgánico) del
        futuro programa (software) que gestionará el futuro sistema informático (si no existe).

        Luego se deben escribir las líneas de código necesarias para el correcto funcionamiento (programación),
        participar
        en las fases de pruebas, confeccionar la documentación técnica, y hacer el seguimiento y el mantenimiento del
        producto.

        El desarrollador puede también capacitar a los usuarios.
    </p>
</section>
<div>
    <p>
        Terminología
        Según el diccionario de la lengua francesa 'Larousse'2​ y la 'Office québécois de la langue française' (en
        español: 'Oficina quebecuense de la lengua francesa'), y aunque esto no es reconocido por el Centre national de
        ressources textuelles et lexicales), el término «développeur»1​ (en español: «desarrollador») se aplica (en el
        dominio de la informática), a una persona que concibe y desarrolla aplicaciones informáticas, o una empresa
        organizada y orientada a desarrollar ese tipo de aplicaciones y su asociado software. Sin embargo, en el caso de
        las personas, es posible distinguir a los desarrolladores por especialidad y formación, o sea, diferenciar entre
        los expertos en el arte del manejo, uso, y creación de software, y los especializados particularmente en todo lo
        relativo a Internet y al manejo de ordenadores (sistemas operativos, programas utilitarios, etc),3​ así como los
        especializados en el sector de las Tecnologías de la información y la comunicación (TICS), grupos todos estos en
        los que se encuentran desarrolladores con las características que se indican seguidamente
    </p>
    <p>
        El desarrollador informático o desarrollador web4​5​ responsable de los códigos-fuente elaborados en diferentes
        lenguajes de programación web (programación con el propósito de hacer páginas web, lo que a menudo es llamado
        programación web o desarrollo web), utilizando entre otros lenguajes de marcas, el HyperText Markup Language
        (HTML) —en español: lenguaje de marcas de hipertexto—, el Cascading StyleSheets (CSS) —en español: Hojas de
        estilo en cascada—, y el Extensible Markup Language (XML) —en español: Lenguaje de Marcas Extensible—, etc.
    </p>
</div>
<footer>
    <p class="destacado">
        Jorge omar uribe rodriguez

    </p>
    <p>Curso:Introduccion a la programacion
    </p>
    <p>jorge.uribe112180@gmail.com

    </p>
</footer>



<body>

</body>

</html>

```

### STYLES.CSS

```
header {
    background-color: black;
    border-radius: 5px;
    display: flex;
    justify-content: center;
    margin-bottom: 7px;
}

header h1 {
    color: red;
}

.contenedor {
    display: flex;
    justify-content: center;
}

.contenedor img {
    width: 500px;
    height: 400px;
    border: solid black 5px;

}

#sombras {
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 3);
}

.destacado {
    color: green;
}

.grande {
    font-size: 20px;
}

#principal {
    color: yellow;
}

section p {
    color: blue;
}

footer {
    background: black;
    border-radius: 5px;
    color: blue;
}

div {
    color: grey;
}

```
