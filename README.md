<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Boliche.ar</title>
    <!-- Agrega los enlaces a los archivos de estilo y scripts de Bootstrap -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="style.css">
    <style>
        /* Estilo adicional para la imagen de la portada */
        #contenedorPortada {
            position: relative;
            width: 100%;
            height: 50vh;
            overflow: hidden;
        }

        #portada {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Estilo adicional para el texto sobre la imagen */
        #textoSobreImagen {
            position: absolute;
            top: 60%;
            right: 20%;
            transform: translate(0, -50%);
            color: rgba(46, 88, 127, 0.9);
            font-size: 2em;
            font-weight: bold;
            padding: 20px; /* Ajusta el espacio alrededor del texto */
            background-color: rgba(255, 255, 255, 0.7); /* Fondo semi-transparente para mejor legibilidad */
            border: 2px solid #2E587F; /* Borde del recuadro */
            border-radius: 10px; /* Bordes redondeados */
        }
    </style>

    <style>
        /* Estilo adicional para las imágenes del carrusel */
        #myCarousel img {
            transition: transform 0.2s;
            width: 30%; /* Ajusta el tamaño según sea necesario */
        }

        #myCarousel img:hover {
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <div id="contenedorPortada">
        <img id="portada" src="img/Portada.jpg" alt="Boliche.ar">
        <div id="textoSobreImagen">Boliche.ar</div>
    </div>
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav mx-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#Calendario">Calendario</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            QuieroFiesta
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#Por Zona">Por Zonar</a>
                            <a class="dropdown-item" href="#Tematicas">Tematicas</a>
                            <a class="dropdown-item" href="#LGTBIQ">LGTBIQ</a>
                            <a class="dropdown-item" href="#Genero Musical">Genero Musical</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#TuPlaylist" target="_blank">Tu Playlist</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Bebidas
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#TragosDeAutor">Tragos de Autor</a>
                            <a class="dropdown-item" href="#Clasicos">Clásicos</a>
                            <a class="dropdown-item" href="#BebidasSinAlcohol">Bebidas sin Alcohol</a>
                        </div>
                    </li>
                </ul>
            </div>
        </nav>
        
    </header>

    <div class="contenedor">
        <div class="login-form">
            <h2>Iniciar Sesión</h2>
            <form action="#" method="post">
                <label for="usuario">Usuario:</label>
                <input type="text" id="usuario" name="usuario" required>
                <label for="contraseña">Contraseña:</label>
                <input type="password" id="contraseña" name="contraseña" required>
                <button type="submit">Ingresar</button>
            </form>
        </div>

        <section id="inicio">
            <h2>Que noche la de anoche</h2>
            <p>Ellxs salieron de fiesta ¿Vos qué esperas?</p>
            
            <div id="myCarousel" class="carousel slide" data-ride="carousel">
                <!-- Diapositivas del carrusel -->
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="img/Fiesta.jpg" width="30" class="d-block w-60" alt="Imagen 1">
                    </div>
                    <div class="carousel-item">
                        <img src="img/Fiesta2.jpg" width="30" class="d-block w-60" alt="Imagen 2">
                    </div>
                    <div class="carousel-item">
                        <img src="img/Fiesta3.jpg" width="30" class="d-block w-60" alt="Imagen 3">
                    </div>
                    <div class="carousel-item">
                        <img src="img/fiesta4.webp"width="30"  class="d-block w-60" alt="Imagen 4">
                    </div>
                    <div class="carousel-item">
                        <img src="img/iamgen5.jpg" width="30" class="d-block w-60" alt="Imagen 5">
                    </div>
                    <div class="carousel-item">
                        <img src="img/imagen6.jpg" width="30" class="d-block w-60" alt="Imagen 6">
                    </div>
                    <!-- Agrega más imágenes según sea necesario -->
                </div>
                
                <!-- Controles del carrusel -->
                <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Anterior</span>
                </a>
                <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Siguiente</span>
                </a>
            </div>
        </section>

        <section id="eventos">
            <header>
                <nav>
                    <ul>
                        <li><a href="#EventosExclusivos">Eventos Exclusivos</a></li>
                        <li><a href="#NewsLetter">News Letter</a></li>
                    </ul>
                </nav>
            </header>
        </section>
    </div>

    <footer>
        <p>Derechos de autor © 2023 Boliche.ar</p>
    </footer>

    <!-- Agrega los scripts de Bootstrap y jQuery al final del cuerpo del documento -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>
</html>

