# UF1-A3-Documentacion-MP4UF1-APUNTES


## Primer Capitulo: MARKDOWN

Este texto esta en *cursiva*
Este texto esta en _cursiva_
Este texto esta en **negrita**
Este texto esta en __negrita__

Este texto está en **_negrita y cursiva_**.

1. Primera opción de menú
2. Seguna opción de menú
3. Tercera opción de menú

* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submenú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

```
<html> 
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    <body>
<html>
```
[Esto es un enlance](http://joan23.fje.edu "Enlance a la web del cole")

![Esto es una foto de prueba](https://github.com/QuicoSanchez/ASIX1-M4-UF1-A3_Apuntes/blob/main/Test.png "Titulo opcional de la imagen")

|Primera Col.|Segunda Col.|3 Col|
|---------------|:------------:|---------:|
|Col 2 es|centrada|35€|
|Col 3 es| derecha|134€|
|Estilo cebra|Gris|Blanco|
|Clase|ASIX1|M4|

-[ ] Opcion A
-[X] Opcion B
-[ ] Opcion C


## Segundo Capitulo: HTML

1. **Informacion**

    - Para que nos de el cuerpo html directamente, pondremos un VScode: (hmtl:%5). 

    - **Clasificacion de palabras**:
        - "<!DOCTYPE html>"significa que empieza aqui el html y para el cierre se utilizara "</html>".
        - Para el lenguaje de html utilizaremos: <html lang="en"> ("en" significa que este html estara en ingles)

        - **Head:** es la parte donde definimos las caracteristicas de la pagina y metemos el contenido no visible a los participantes.

            - Meta charset: Es el idioma del teclado
            - Meta name (viewport): Es lo que define como se va a mostrar los contenidoos en la pantalla.
            - Content: Son las caracteristicas de los lenguajes, como anchura, longuitud, escala...

        - **Body:** Es donde meteria todo el contenido de la pagina visible

            - Etiquetas Bloque: Titulos, parrafos, listas y las tablas
            - Etiquetas Lineas: Enlaces, estilos  (negrita, subrayado...), Imagenes


            - <ol>Es una lista ordenada
                <li>Primer elemento</li>
                <li>Segunda elemento</li>
                <li>Tercer elemento</li>
              </ol>
            - <ul>Es una lista desordenada
                <li>Primer elemento</li>
                <li>Segunda elemento</li>
                <li>Tercer elemento</li>
              <ul>
        - La etiqueeta <b> y <strong> son para poner las palabras en negrita

    1.1**Tablas**
    - Ejemplo de como hacer una tabla

    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tablas</title>
    <style>
        .textoazul{
            color: rgb(1, 136, 253);
        }
    </style>
</head>
<body>
    <table border="1">
        <thead>
            <tr
                style="color: red;text-align: center;">
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </thead>
        <tbody style="background-color: blueviolet;text-align: center; color: aliceblue;">
            <tr id="primerafila">
                <td>1r</td>
                <td>Paco Martinez</td>
                <td>14:25</td>
            </tr>
            <tr class="textoazul">
                <td>2r</td>
                <td>Pau Lopez</td>
                <td>14:50</td>
            </tr>
            <tr class="textoazul">
                <td>3r</td>
                <td>Joel Gallego</td>
                <td>15:30</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </tfoot>
    </table>
</body>
</html>

## Tercer Capitulo: CSS
    -  Para darle estilo utilizamos la etiqueta <style>
        - En esta estiqueta podemos utilizar varias funicones siempres separadas por un **;**
        - Class 
        - Id 
        - Background-color (color de fondo)
        - Text-align: center (para centrar el texto)
        - Color (para cambiar el color de las palabras)
