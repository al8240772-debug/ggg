<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Broma</title>
    <style>
        body {
            font-family: 'Arial Black', Gadget, sans-serif;
            background-color: #000;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }

        .video-container {
            width: 100%;
            max-width: 750px;
            border: 3px solid #444;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 0 25px rgba(255, 255, 255, 0.1);
        }

        video {
            display: block;
        }

        .mensaje {
            margin-top: 30px;
            font-size: 2.5rem;
            color: #f1c40f; /* Amarillo vibrante */
            text-align: center;
            text-transform: uppercase;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.8);
        }

        .link-contenedor {
            margin-top: 25px;
        }

        .boton-link {
            display: inline-block;
            padding: 15px 30px;
            background-color: #3498db; /* Azul llamativo */
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-size: 1.2rem;
            transition: transform 0.2s, background-color 0.2s;
        }

        .boton-link:hover {
            background-color: #2980b9;
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <div class="video-container">
        <video width="100%" autoplay muted controls loop>
            <source src="nombre-de-tu-video.mp4" type="video/mp4">
            Tu navegador no soporta el video.
        </video>
    </div>

    <div class="mensaje">
        ¡Es broma este es el verdadero video!
    </div>

    <div class="link-contenedor">
        <a href="#" class="boton-link">Haz clic aquí para ver el contenido</a>
    </div>

</body>
</html>
