<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


## Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css
### Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

## SOLUCIÓN

## Documento HTML

```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title><input type="color" value="#de2020" />
    <link rel="stylesheet" href="Style.css">
    <p>Suscribete a nuestro canal</p>
    <button class="joinBtn">Subscribe</button>
    <p>Paginas que quizas ayas visitado:</p>
    <ul>
        <li>
            <a href="https://developer.mozilla.org">MDN Web Docs</a>
        </li>
        <li>
            <a href="https://www.youtube.com/YouTube">Google</a>
        </li>
    </ul>
    <p>Paginas que poco esten en tu historial:</p>
    <ul>
        <li>
            <a href="https://developer.mozilla.org/missing-3">Random MDN page</a>
        </li>
        <li>
            <a href="https://example.com/missing-3">Random Example page</a>
        </li>
        <P>
            Simple: ejemplo en blanco
            En eventuales navegadores compatibles, la :blankpseudoclase permitirá a los desarrolladores resaltar de
            alguna manera los controles de entrada que no son necesarios, pero que aún no tienen contenido completo, tal
            vez como un recordatorio para los usuarios.
        </P>
    </ul><textarea></textarea>
    <table border="1">
        <p>:-moz-arrastrar-sobre</p>
        <tr>
            <td width="100px" height="100px">Arrastrar</td>
        </tr>
    </table>
    <div> </div>
    <p>Cuando el usuario visite el enlace por primera vez, tendrá un fondo rojo. Cuando el usuario haga clic en el
        enlace, tendrá un fondo verde.</p>
    <a href="#">Enlace</a>
    <p>Ejemplos
        Este ejemplo altera la apariencia del fondo de un cuadro dependiendo de si su ventana está activa o no.</p>
    <div id="mybox">
        <p>Esta es una caja!</p>
    </div>
    <P>
        EJEMPLO
    </P>

    <input type="range" min="0" max="100" step="5" value="50" /><DIv>

        
        <video src="video.mp4" controls></video>
        <video controls preload="metadata">
        <source src="video.mp4" type="video/mp4" />
        <source src="video.webm" type="video/webm" />
        <track
          label="English"
          kind="subtitles"
          srclang="en"
          src="subtitles.vtt"
          default />
      </video>

    </DIv>


</head>

<body>

</body>

</html>

```

## Documento CSS

```
input[type="color"]::-moz-color-swatch {
        border-radius: 10px;
        border-style: none;
      }

      .joinBtn {
        width: 10em;
        height: 5ex;
        background-image: linear-gradient(135deg, #f34079 40%, #fc894d);
        border: none;
        border-radius: 5px;
        font-weight: bold;
        color: white;
        cursor: pointer;
      }
      
      .joinBtn:active {
        box-shadow: 2px 2px 5px #fc894d;
      }


      p {
        font-weight: bold;
      }
      
      a:any-link {
        color: forestgreen;
        text-decoration-color: hotpink;
      }

      textarea:blank {
        border: 3px solid red;
      }

      td:-moz-drag-over {
        color: red;
      }

      div {
        border: 4px solid red;
      }
      
      :-moz-only-whitespace {
        border-color: rgb(4, 246, 4);
      }

      p {
        background-color: white;
      }
      
      p:hover {
        background-color: gray;
      }

      #mybox {
        background: linear-gradient(to bottom, yellow, cyan);
        width: 200px;
        height: 200px;
      }
      
      #mybox:-moz-window-inactive {
        background: cyan;
      }

      input[type="range"]::-moz-range-progress {
        background-color: green;
        height: 1em;
      }

      :current(p, span) {
        background-color: yellow;
      }

      video {
        height: 300px;
        margin-bottom: 40px;
    }

    ```