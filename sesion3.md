<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 

## Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

4. Imagenes
2.  Videos
4.  Audios
2.  Inline Frame
Utiliza encabezados para títulos en cada elemento ```(<h1>...<h6>).```

Crea una descripción para cada elemento utilizando párrafos ```(<p>).```

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa ```<strong>``` para resaltar texto importante.
- Utiliza ```<br>``` para insertar saltos de línea si es necesario.
- Agrega ```<span>``` para aplicar estilos específicos a porciones de texto.
- Emplea ```<i>``` para enfatizar o dar énfasis a palabras o frases.
- Utiliza ```<u>``` para subrayar texto cuando sea necesario.
- Considera el uso de ```<div>``` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## SOLUCIÓN

## EJERCICIO 3 ACTIVIDAD

```
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: red;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(73, 27, 241);
        }

        footer {
            background-color:#333333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>imagenes</h2>
        <img src="foto 1.avif" style="width: 300px;" alt="">
        <p>la tecnologia el internet se refiere a los objectos ficicos,como dispositivos electronicos que estan
            conectados a interntet y pueden intercambiar datos entre si. esta interconexion permite recopilar datos
            entre si,automatizar tareas y mejorar la eficacia en diversos campos,como la industria,la salud,el trasporte
            y el hogar inteligente.</p><img src="foto 2.avif" style="width: 300px">
        <p>
            El mundo avanza e innovan crean mejores tecnologias para interactuar y comunicarsen entre si a niveles
            globales

        </p>
        <img src="foto 3.avif" style="width: 300px">
        <p>
            Estas computadoras son dispositivos móviles diseñados para ser transportados fácilmente y utilizados en
            diferentes lugares, lo que les proporciona a los usuarios flexibilidad y portabilidad en su trabajo, estudio
            y entretenimiento. Aquí hay algunas formas en las que la gente utiliza sus equipos portátiles: 1. **Trabajo
            Remoto**: Muchas personas utilizan laptops para trabajar desde lugares distintos a la oficina,
            permitiéndoles ser productivos desde casa, cafeterías, espacios de coworking o cualquier otro lugar con
            conexion a internet. 2. **Est.
        </p>
        <img src="foto 4.avif" style="width: 300px" alt="">
        <p>
            La interacción entre el mundo global y la tecnología ha sido uno de los aspectos más destacados y
            transformadores de la sociedad contemporánea. La tecnología ha jugado un papel fundamental en la creación de
            una aldea global interconectada, donde la información, las personas y las ideas pueden fluir a través de
            fronteras geográficas de manera instantánea. Aquí hay algunos puntos clave sobre cómo la tecnología ha
            impactado en el mundo global: 1. **Comunicación Global Instantánea**: La tecnología ha permitido una
            comunicación global instantánea a través de la telefonía móvil, el correo electrónico, las redes sociales y
            las aplicaciones de mensajería. Personas de diferentes partes del mundo pueden interactuar en tiempo real,
            lo que ha acortado las distancias y ha permitido que las noticias y las tendencias se difundan a nivel
            internacional de manera rápida y eficiente. 2. **Acceso a la Información**: Internet
        </p>





    </section>

    <section>
        <h2>Videos</h2>
        <video src="video 1.mp4" controls></video>
        <p>
            En el mundo actual, varios países están demostrando un fuerte compromiso con la sostenibilidad y están
            adoptando medidas para convertirse en modelos de sociedades futuristas sostenibles. Estos países están
            enfocados en reducir su huella ecológica, promover energías limpias, conservar recursos y abordar los
            desafíos ambientales de manera innovadora. Aquí hay algunos ejemplos de países que se destacan por sus
            enfoques futuristas hacia la sostenibilidad: 1. **Dinamarca**: Dinamarca es líder en energía eólica y está
            trabajando para ser libre de combustibles fósiles para 2050. Copenhague, su capital, es conocida por su
            enfoque en la movilidad sostenible, la planificación urbana centrada en las bicicletas y la infraestructura
            verde. 2.
        </p>
        <video src="video 7.mp4" style="height: 300px" controls></video>
        <p>
            "Colapso y Tecnología: Una Perspectiva en Números" En este video, exploramos la interacción entre el colapso
            y la tecnología a través de datos y cifras impactantes. Analizamos cómo la tecnología está desempeñando un
            papel clave en abordar los desafíos que podrían llevarse a cabo al colapsar, al mismo tiempo que plantean
            nuevos problemas. Desde la crisis climática hasta la ciberseguridad, estos números destacan la urgencia de
            una acción informada y sostenible. 1. **Crisis Climática y Energía**: - 415 ppm: Concentración de CO2 en la
            atmósfera (2021). - 80%: Porcentaje de la energía mundial procedente de combustibles fósiles. - 30 años:
            Tiempo restante para evitar impactos climáticos irreversibles.
        </p>


        <section>
            <h2>Audios</h2><audio src="audio 1.mp3" controls></audio>
            <p>La tecnología global ha transformado nuestra forma de vida en todos los aspectos. Desde la comunicación
                instantánea hasta el acceso a información ilimitada, vivimos en un mundo interconectado donde la
                tecnología desempeña un papel central en la manera en que trabajamos, aprendemos y nos relacionamos.</p>

            <audio src="audio 2.mp3" controls></audio>
            <p>
                La tecnología global ha creado oportunidades sin precedentes. Gracias a la digitalización y la
                conectividad, las empresas pueden expandirse más allá de las fronteras y las personas pueden aprender y
                colaborar a nivel mundial. Sin embargo, también debemos abordar los problemas de seguridad cibernética y
                equidad digital para asegurarnos de que todos se beneficien.


            </p>

            <audio src="audio3.mp3" controls></audio>
            <p>
                Vivimos en una era impulsada por la tecnología global. Desde la inteligencia artificial hasta la
                Internet de las Cosas, la innovación tecnológica está revolucionando industrias enteras y cambiando la
                forma en que interactuamos con el mundo. Es fundamental que sigamos explorando nuevas formas de
                aprovechar estas herramientas para un futuro más sostenible y eficiente.
            </p>

            <audio src="audio 4.mp3" controls></audio>
            <p>
                La tecnología global está redefiniendo los límites de lo posible. La forma en que trabajamos, nos
                comunicamos y nos entretenemos ha evolucionado poderosamente gracias a la interconexión tecnológica. Sin
                embargo, no debemos olvidar los aspectos éticos y de privacidad al avanzar en esta era digital, para
                asegurarnos de que nuestra sociedad progrese de manera equitativa y responsable.
            </p>

        </section>

        <section>
            <h2>iFrames</h2>

            <iframe width="500" height="300" src="https://www.youtube.com/embed/KYjwVEGCnjM"
                title="Yo Aprovecho la Tecnología – Uso responsable de nuevas tecnologias." frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                allowfullscreen></iframe>
            <p>
                En conclusión, la tecnología es una herramienta poderosa que puede enriquecer y simplificar nuestras
                vidas de muchas maneras. Aprovecharla de manera efectiva implica encontrar un equilibrio entre su uso y
                el mundo real, así como ser consciente de cómo puede influir en nuestras interacciones y experiencias.
                Algunos puntos clave para aprovechar la tecnología de manera positiva son: 1. **Propósito y Enfoque**:
                Utiliza la tecnología con un propósito definido. Establece metas claras para su uso y evita caer en
                patrones de consumo pasivo. La tecnología debe ser una herramienta que respalde tus objetivos y valores.
            </p>

            <p>Contenido sobre iframes...</p>
            <iframe src="https://es.wikipedia.org/wiki/Tecnolog%C3%ADa" width="500" height="500" frameborder="0"></iframe>
        </section>

        <footer>

        jorge omar uribe rodriguez 
            <br>
            <br>
            CESDE
            <br>
            <br>
            &copy;2023
        </footer>

</body>

</html>

```





