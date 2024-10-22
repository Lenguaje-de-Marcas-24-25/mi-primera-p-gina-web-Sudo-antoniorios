# Antonio Ríos

## Mi primera página web

### Este es el código de mi página en html

<!DOCTYPE html>
<html lang="es">

<!-- Aquí empieza la cabecera de mi pagina -->
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Aquí el titulo de mi pagina -->
    <title>¿Qué es HTML?</title>

    <!--  aqui defino los estilos de mi pagina -->

    <style>

        body {
            font-family: Arial, sans-serif;
        }

        h1 {
            font-size: 2em;
        }

        h2 {
            font-size: 1.5em;
        }

        p {
            font-size: 1em;
        }

        img {
            display: block;
            margin: 0 auto;
            width: 150px;
        }

        ul {
            list-style-type: circle;
        }

        a {
            color: blue;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid black;
            padding: 10px;
        }

        th {
            text-align: left;
        }
    </style>
</head>

<!-- Aqui empieza el cuerpo de mi pagina -->
<body>

    <h1>HTML</h1>
    
    <img src="HTML5_logo_and_wordmark.svg.png" alt="HTML Logo">
    
    <h2>¿Qué es HTML?</h2>
    <p>
        HTML, sigla en inglés de <strong>HyperText Markup Language</strong> (lenguaje de marcas de hipertexto), 
        hace referencia al lenguaje de marcado para la elaboración de páginas web. Es un estándar que sirve de 
        referencia del software que conecta con la elaboración de páginas web en sus diferentes versiones, define 
        una estructura básica y un código (denominado código HTML) para la definición de contenido de una página web, 
        como texto, imágenes, videos, juegos, entre otros.
    </p>
    <p>Para más detalles haz click en <a href="#">este enlace</a></p>

    <h2>Editores de texto recomendados</h2>
    <p>Algunos editores de texto recomendados son:</p>
    <ul>
        <li>Notepad - <a href="#">Enlace para descargar</a></li>
        <li>SublimeText - <a href="#">Enlace para descargar</a></li>
        <li>Dreamweaver - <a href="#">Enlace para descargar</a></li>
        <li>Gedit - <a href="#">Enlace para descargar</a></li>
        <li>Notepad++ - <a href="#">Enlace para descargar</a></li>
    </ul>

    <h2>Navegadores Web</h2>
    <p>Los siguientes navegadores permiten visualizar páginas web:</p>

    <!-- Aqui inserto un tabla -->
    <table>
        <tr>
            <th>Nombre</th>
            <th>Enlace descarga</th>
        </tr>
        <tr>
            <td>Firefox</td>
            <td><a href="#">Descargar</a></td>
        </tr>
        <tr>
            <td>Microsoft Edge</td>
            <td><a href="#">Descargar</a></td>
        </tr>
        <tr>
            <td>Google Chrome</td>
            <td><a href="#">Descargar</a></td>
        </tr>
        <tr>
            <td>Safari</td>
            <td><a href="#">Descargar</a></td>
        </tr>
    </table>

</body>
</html>