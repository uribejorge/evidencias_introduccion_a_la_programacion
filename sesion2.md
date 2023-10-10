<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


## Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

#### Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto


## index.html

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESFERA DIGITAL DE INNOVACION

    </title>
</head>

<body>
    <HEader>
        <h1>INNOVATION DIGITAL SPHERE


    </HEader>
    <Nav><a href="http://127.0.0.1:5500/about.html">acerca de la empresa
        </a><a href="http://127.0.0.1:5500/contact.html">contacto de la empresa</a>
        
    </Nav>

        <main>
            <p>Bienvenidos a mi sitio sobre la empresa esfera digital de innovacion</p>
            <p>la empresa de innovacion digital ofrece estos servicios a tu alcance como desarrollo de sotfware personalizados, diseño de aplicaciones moviles,consultoria de ciberseguridad,implementacion de soluciones en la nube,diseños de sitios web,analisis de datos y mas. En cuanto a productos: dispositivos electronicos, computadoras,celulares,consolas de video juegos y accesorios. </p>
        </main>

        <footer>
            <p>copyright 2023 - jorge uribe</p>
            <p>jorge.uribe112180@gmail.com

            </p>
        </footer>
        

</body>
</html>

```


## About.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre nosotros    </title>
</head>
<body><header>
    <h1>En esfera digital de innovación, estamos en el corazon de la revolucion tecnologica,ofreciendo una amplia gama de servicios y productos para satisfacer todas tus nesecidades digitales. Desde los dispositivos mas vanguarditas,como celulares y computadoras, hasta las consolas de videojuegos mas emocionantes y accesorios de ultima generación,estamos aqui para llevar innovacion directamente a tus manos.Pero no nos detenemos ahi. Somos mas que una tienda de tecnologia. Nuestra experencia se extiende a la consultoria de ciberseguridad,donde proteger tus activos digitales es nuetras prioridad.Ademas, Te guiamos en la migracion hacia la nube,optimizando tus operaciones y llevando su infraestruturas al siguiente nivel.En esfera digital de innovacion,no solo seguimos las tendencias,las creamos innovamos.Nuestro compromiso con la excelencia y la sastifacion del cliente nos impulsa a brindarte soluciones tecnologicas que trasforman la manera en que interactuas con el mundo digital.Unete a nosotros y descubre el universo de posibilidades digitales ilimitades.</h1>

</header>
<nav>
    <a href="http://127.0.0.1:5500/index.html">inicio</a>
    <br>
    <a href="http://127.0.0.1:5500/contact.html">contacto de la empresa </a>
</nav>
<section><h2>


    
    La historia de Esfera Digital de Innovación comenzó en un modesto garaje, donde un grupo de mentes creativas se reunía para discutir cómo podrían llevar la tecnología a nuevas alturas. Pronto, su pasión se tradujo en una gama de productos que iban desde celulares de última generación hasta consolas de videojuegos que llevaban a los jugadores a mundos asombrosos.
    
    Pero esta empresa no solo se trataba de productos; su compromiso con la excelencia abarcaba mucho más. Vieron la necesidad de brindar seguridad en un mundo digital cada vez más complejo. Así nació su división de consultoría de ciberseguridad, donde se dedicaban a proteger a las empresas y personas de las amenazas en línea.
    
    Con el tiempo, Esfera Digital de Innovación no solo se estableció como un líder en productos tecnológicos, sino que también se convirtió en un asesor confiable en la transformación digital. Su experiencia en implementación en la nube y soluciones digitales personalizadas ayudó a innumerables empresas a optimizar sus operaciones y a abrazar el futuro digital con confianza.
    
    La historia de Esfera Digital de Innovación es una de pasión, innovación y adaptación constante. En un mundo en constante evolución, la empresa se mantuvo firme en su compromiso de brindar soluciones tecnológicas que marcan la diferencia. Desde su modesto comienzo hasta convertirse en un referente en la industria, Esfera Digital de Innovación continúa trazando un camino hacia el futuro digital, donde las posibilidades son infinitas."
    
    </h2>
<p>fundada en el 2019</p>
<article>
    <h3>mision y vision</h3>
<p>MISION:"Nuestra misión en Esfera Digital e Innovación es ser el socio confiable y catalizador de la transformación digital para empresas de todo tamaño y sector. Nos comprometemos a ofrecer soluciones tecnológicas y consultoría de vanguardia que potencien la adaptación, la eficiencia y el crecimiento sostenible de nuestros clientes. Mediante un enfoque colaborativo y una comprensión profunda de sus necesidades, buscamos impulsar la innovación, desbloquear nuevas oportunidades y marcar el camino hacia un futuro digital emocionante y lleno de posibilidades."</p>
<P>Visión:
    "En Esfera Digital e Innovación, visualizamos un mundo empresarial donde la tecnología no es solo una herramienta, sino un motor poderoso de cambio y progreso. Queremos ser reconocidos como líderes influyentes en la industria de la tecnología y la consultoría digital, impulsando la evolución de las organizaciones hacia la excelencia digital. Buscamos constantemente ampliar nuestros horizontes, inspirar la creatividad y ser los facilitadores de la transformación que allana el camino hacia el éxito en la era digital. A través de nuestra pasión por la innovación y nuestra dedicación a nuestros clientes, aspiramos a ser la opción preferida para aquellos que buscan navegar con confianza por las aguas de la revolución tecnológica."</P></article></section>
    <Footer>
        <P>copyright 2023 - jorge uribe</P>
    </Footer>

    
</body>
</html>

```

## Contact.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contacto de la empresa </title>
</head>
<body>
    <header>
        <h1>contacto de la empresa </h1>
    </header>
    <nav>
        <a href="http://127.0.0.1:5500/index.html">inicio</a>
        <a href="http://127.0.0.1:5500/about.html">acerca</a>
    </nav>
    <main>
        <form action="">
            <label for="nombre:">nombre: esfera digital de innovacion
             
            </label><input type="text" id="nombre"><br>
            <label for="email">email:jorge.uribe112180@gmail.com</label>
            <input type="email" id="email"><br>

            <label for="mensaje">mensaje:</label><br>
            <textarea name="" id="mensaje"></textarea><br>
            <input type="submit" value="enviar">
        </form>
        <aside>
            <h3>ubicacion</h3>
            <p>calle 45 # 35-20</p>
        </aside>
        
    </main>
    <footer>
        <p>copyright 2023 - jorge uribe</p>
    </footer>
    
</body>
</html>

`````