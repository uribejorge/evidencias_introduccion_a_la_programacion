<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


## Actividad: Crear una tabla HTML con información sobre productos.
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

## SOLUCIÓN

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <table cellpacing="9px" cellpadding="12px" border="1px" valing="center">
        <thead>
            <tr>
                <th>codigo</th>
                <th>nombre</th>
                <th>descripcion</th>
                <th>precio</th>
                <th>stock</th>
                <th>fecha de creacion</th>
            </tr>

        </thead>
        <tbody>
            <tr>
                <td rowspan="3">001</td>
                <td rowspan="3">ipnone 14 pro max</td>
                <td>

                    El iphone 14 pro max es el smarphone mas potente del mercado. Cuenta con una pantalla OLED de 6,7
                    pulgadas,un prcesador A 16 Bionic y un sitema de camaras de 48 megapixeles

                </td>
                <td>4.899.000 cop</td>
                <td>10</td>
                <td>2022-09-21</td>

            <tr>
                <td>
                    El iphone 14 pro max esta disponible en cuatro colores:grafito,plata,oro y sierra.
                </td>
                <td>100</td>
            </tr>
            </tr>

        </tbody>
        <tbody>
            <td rowspan="3"> 002</td>
            <td rowspan="3">Macbook pro m2 pro</td>
            <td>El macbook pro m2 proes el nuevo portatil profesional de apple. cuenta con un procesador M2 pro, una
                pantalla liquida retina XDR y un sistema de camaras truedepth con camara face timeHD</td>
            <td>10.499.000 COP</td>
            <Td>10</td>
            <td>2023-06-06

            </td>
            <tr>
                <td>El macbook pro m2 pro esta disponible en dos colores: gris espacial y plata.</td>
                <td>75</td>
            </tr>



            </Td>
        </tbody>
        <tbody>
            <td rowspan="3">0010</td>
            <td rowspan="3">Nitendo Switch OLED </td>
            <td>El nitendo Switch OLED es la version mejorada de la consola de nitendo Switch.Cuenta con una pantalla
                OLED de 7 pulagas, mas almacenamiento y un soperte ajustable

            </td>
            <td>1.099.000 cop</td>
            <td>10</td>
            <td>2021-10-08</td>
            <tr>
                <td> El nitendo Swith OLED esta disponible en dos colores: blanco y negro.</td>
                <td>75


                </td>

            </tr>
        </tbody>
        <tbody>
            <td rowspan="3">0050</td>
            <td rowspan="3">galeria de equipos de alta gama </td>
            <td style="display: flex;"> <img src="foto iphone 14 -2.jpg" Style="width: 200px;" >
                <h3>la mejor tecnologia del mercado </h3>
                <img src="tablet 1.jpg"Style="width: 200px" >
                <h3>disponible en todos los modelos </h3><img src="fotos de televisores alta gama.jpg"Style="width: 200px" alt="">
                <h3>utilizan tecnologias avanzandas de patalla como OLED o QLED</h3>
            <td>6.900.000cop 7.000.000cop  5.200.000cop
            <td>10
            <td>2023-08-24</td>
            <tr>
            <td>Todos los equipos de alta gama se encuentran en todos los medelos 
            <td>75</td>
            

            </td></tr><tbody>
            <td rowspan="3">0055</td>
            <td rowspan="3">tendencias en tecnologias de alta gama</td>
            <td rowspan="3">se manejan celulares android y apple  </td>
            <td rowspan="3">mastercard, visa </td>
            <td rowspan="3">10</td>
            <td rowspan="3">2023-08-24</td></tr>
        </tbody>
        <tbody>
            <td></td>
            <td></td>
        <td>Disponemos de todos las marcas del mercando en nuestras tiendas
        </td><td>75</td>
        

        
                
            </td>

            </tbody>

            

            </td>

            </tr>

            </td>

            </td>


            </td>

            </td>


            </tbody>

            </td>

            </td>

            </td>

        </tbody>

    </table>



    </thead>


</html>

```

