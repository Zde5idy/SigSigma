# SigSigma
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página web</title>
    <link rel="stylesheet" href="estilos.css">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;700&display=swap" rel="stylesheet">
    <link href='https://unpkg.com/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    
    <header class="header" id="inicio">
        <img class="hamburguer" src="img/hamburguesa.svg" alt="">
        <nav class="menu-navegacion">
                <a href="#inicio">Inicio</a>
                <a href="#servicio">Servicio</a>
                <a href="#galeria">Portafolio</a>
                <a href="#expertos">Especializados</a>
                <a href="#footer">Contacto</a>
                <a href="loteria.html">Ir al Juego</a>
                <a href="Itil.html">Ir ITIL Ciclo de Vida</a>
                <a href="mapa.html">Ir  Diagrama</a>
        </nav>
        <div class="contenedor head">
            <h1 class="titulo">Metodologias</h1>
            <p class="copy">Sairy Deidy</p>
        </div>
        
    </header>
    <main>
        <section class="services contenedor" id="servicio">
            <h2 class="subtitulo">Servicio</h2>
            <div class="contenedor-servicio">
                <img src="img/checklist.svg" alt="">
                <div class="checklist-servicio">
                    <div class="service">
                        <h3 class="n-service"><span class="number">1</span>¿Qué es Six Sigma?</h3>
                            <p> La metodología Six Sigma fue un concepto creado en los 80 por Bill Smith. 
                            Esta metodología fue creada para reducir la variabilidad para reducir o eliminar 
                            los defectos o fallos en la entrega de un producto o servicio al cliente/usuario. 
                            El objetivo de Six Sigma es conseguir detectar 3,4 defectos por millón.</p>

                        <h3 class="n-service"><span class="number">*</span>Six Sigma?</h3>
                            <p> Definidas en un procedimiento documentado
                                Provistas (la organización) de los medios y formación necesarios
                                Ejecutadas de un modo sistemático, universal y uniforme (institucionalizadas)
                                Medidas
                                Verificadas</p>
                    </div>
                    
                </div>
            </div>
        </section>
        <section class="gallery" id="galeria">
            <div class="contenedor">
                <h2 class="subtitulo">Galeria</h2>
                <div class="contenedor-galeria">
                    <img src="img/img2.jpg" class="img-galeria" alt="Hola">
                    <img src="img/img3.png" class="img-galeria" alt="">
                    <img src="img/img4.png" class="img-galeria" alt="">
                    <img src="img/img5.png" class="img-galeria" alt="">
                    <img src="img/img6.jpg" class="img-galeria" alt="">
                    <img src="img/img7.webp" class="img-galeria" alt="">
                </div>
            </div>
        </section>
        <div class="imagen-light">
            <img src="img/close.svg" alt="" class="close">
            <img src="img/close.svg" alt="" class="agregar-imagen">
        </div>
        <section class="contenedor" id="expertos">
            <h2 class="subtitulo">Expertos en:</h2>
            <section class="experts">
                <div class="cont-expert">
                    <img src="img/pie_chart.svg" alt="">
                    <h3 class="n-expert">El Modelo de Madurez de Capacidades o CMM</h3>
                    <p>Modelo de Madurez de Capacidades conocido por las siglas CMM es 
                       un modelo de evaluación de los procesos de una organización. Fue 
                       desarrollado inicialmente para los procesos relativos al desarrollo
                        e implementación de software por la Universidad Carnegie Mellon para 
                        el SEI (Software Engineering Institute).</p>
                </div>
                <div class="cont-expert">
                    <img src="img/search_engine.svg" alt="">
                    <h3 class="n-expert">El CMM</h3>
                    <p>es un marco que describe una trayectoria de mejora evolutiva
                       de loselementos claves de un proceso software partiendo de un 
                       proceso maduro hasta llegar a un proceso maduro y disciplinado. 
                       Incluye prácticas de planificación, ingeniería, gestión del desarrollo 
                       y mantenimiento de software con el objetivo de mejorar la capacidad de 
                       las organizaciones para satisfacer sus objetivos de costo, calendario, 
                       funcionalidad y calidad del producto.</p>
                </div>
                <div class="cont-expert">
                    <img src="img/security.svg" alt="">
                    <h3 class="n-expert">Características</h3>
                    <p>Mide la capacidad del proceso seguido para desarrollar software 
                        incrementando la pre dicivilidad en cuanto a costos, tiempos y calidad lograda.
                        Es el modelo más utilizado en la industria de software.
                        No contempla todas las necesidades de la organización, por lo que se fueron 
                        agregando otros modelos que daban solución a los problemas detectados.
                        Este modelo establece un conjunto de prácticas o procesos clave agrupados 
                        en Áreas Clave de Proceso (KPA – Key Process Area). Para cada área de proceso 
                        define un conjunto de buenas prácticas que habrán de ser:</p>
                </div>
            </section>
        </section>
    </main>

    <footer id="footer">
        <div class="contenedor footer-content">
                <div class="contact-us">
                    <h2 class="brand">Sairy Mosquera Deidy Zuleta</h2>
                    <p>Somos expertos en metodologias Sig Sigma</p>
                </div>
                <div class="social-media">
                    <a href="./" class="social-media-icon">
                        <i class='bx bxl-facebook'></i>
                    </a>
                    <a href="./" class="social-media-icon">
                        <i class='bx bxl-twitter' ></i>
                    </a>
                    <a href="./" class="social-media-icon">
                        <i class='bx bxl-instagram' ></i>
                    </a>
                </div>
        </div>
        <div class="line"></div>
    </footer>
    <script src="js/menu.js"></script>
    <script src="js/lightbox.js"></script>
</body>
</html>
