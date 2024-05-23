<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARIEL PRODUCCIONES - Fotografía</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #5d5c61;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 2em 0;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 0.5em;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 1em;
            justify-content: center;
        }
        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }
        footer {
            background-color: #5d5c61;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>ARIEL PRODUCCIONES</h1>
        <p>Capturando momentos, creando recuerdos</p>
    </header>
    <div class="container">
        <section>
            <h2>Sobre mí</h2>
            <p>
                ¡Hola! Soy Ariel, un apasionado de la fotografía. Mi objetivo es capturar la belleza del mundo a través de mi lente. Aquí podrás encontrar una selección de mis trabajos y proyectos. Espero que disfrutes de mi visión artística tanto como yo disfruto creándola.
            </p>
        </section>
        <section>
            <h2>Galería</h2>
            <div class="gallery">
                <img src="foto1.jpg" alt="Descripción de la foto 1">
                <img src="foto2.jpg" alt="Descripción de la foto 2">
                <img src="foto3.jpg" alt="Descripción de la foto 3">
                <img src="foto4.jpg" alt="Descripción de la foto 4">
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 ARIEL PRODUCCIONES. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
