
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InnoFusion Studios - Desarrollo de Software, Diseño Gráfico y Análisis de Datos</title>
    <style>
        /* Estilos para el menú de navegación desplegable */
        #main-container {
            background-color: #333;
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        .menu-button {
            background-color: transparent;
            color: #10cf96;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 2;
        }

        .menu-content {
            list-style: none;
            padding: 0;
            background-color: #333;
            width: 0; /* Inicialmente oculto */
            height: 100%;
            overflow: hidden;
            transition: 0.3s;
            position: fixed;
            top: 0;
            left: 0;
        }

        .menu-content li {
            margin: 20px 0;
        }

        .menu-content a {
            text-decoration: none;
            color: #fff;
        }

        .menu-content a:hover {
            text-decoration: underline;
        }

        /* Estilo para el botón de cerrar el menú */
        .close-button {
            color: #fff;
            text-decoration: none;
            position: absolute;
            top: 10px;
            right: 10px;
        }

        body {
            font-family: Arial, sans-serif;
        }
        header {
            background-color: #272525;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        header img {
            max-width: 400px; 
        }
        section {
            padding: 20px;
        }
        .software {
            background-color: #af8585;
        }
        .diseno {
            background-color: #e0e0f0;
        }
        .analisis {
            background-color: #d0d0f0;
        }
    
    </style>
</head>
<body>
    <div id="main-container">
        <span class="menu-button" onclick="openMenu()">&#9776;</span> <!-- Icono de hamburguesa -->
        <ul class="menu-content" id="menu">
            <a href="javascript:void(0)" class="close-button" onclick="closeMenu()">&times;</a> <!-- Icono de cierre -->
            <li><a href="software.html">Software Desarrollados</a></li>
            <li><a href="design.html">Diseño Gráfico</a></li>
            <li><a href="data.html">Analistas de Datos</a></li>
<!-- Otras opciones del menú -->

        </ul>
    </div>
    <header>
        <img src="Logopony .png" alt="Logo de InnoFusion Studios">
        <h1>InnoFusion Studios</h1>
        <p>Tu solución integral en Desarrollo de Software, Diseño Gráfico y Análisis de Datos</p>
    </header>
    <section style="background-color: #f0f0f0;">
        <h1>Bienvenidos a InnoFusion Studios</h1>
  <p>Somos una empresa líder en Desarrollo de Software, Diseño Grafico y Analistas de Datos, dedicada a impulsar la innovación y el crecimiento de tu negocio. En InnoFusion Studios, entendemos que cada empresa es única, y por lo tanto, sus necesidades también lo son.</p>
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <style>
          /* Añadir estilos para centrar los cuadros en el lado derecho */
          .container {
              display: flex;
              justify-content: flex-end; /* Cambiamos justify-content a flex-end */
              align-items: center;
              height: 100vh;
          }
      
          .flip-container {
              perspective: 1000px;
              width: 250px;
              height: 250px;
              display: inline-block;
              margin: 20px;
              cursor: pointer;
          }
      
          .flip-container.hover .flipper {
              transform: rotateY(180deg);
          }
      
          .flipper {
              width: 100%;
              height: 100%;
              transform-style: preserve-3d;
              transition: transform 0.5s;
          }
      
          .front, .back {
              width: 100%;
              height: 100%;
              position: absolute;
              backface-visibility: hidden;
          }
      
          .front {
              background-color: #49a2eb;
              display: flex;
              justify-content: center;
              align-items: center;
              font-size: 24px;
          }
      
          .back {
              background-color: #aaaaaa;
              transform: rotateY(180deg);
              display: flex;
              flex-direction: column;
              justify-content: center;
              align-items: center;
              font-size: 20px;
          }
      
          /* Estilo para el símbolo ↻ */
          .symbol {
              position: absolute;
              bottom: 10px;
              right: 10px;
              font-size: 24px;
          }
      </style>    
  </head>
  <body>
      <div class="container"> <!-- Cambiamos la clase de "center-container" a "container" -->
          <div class="flip-container">
              <div class="flipper">
                  <div class="front">
                      Misión
                      <div class="symbol">↻</div>
                  </div>
                  <div class="back">
                      <img class="icon" src="Mision.png" alt="Icono de Misión" width="55" height="55">
                      <p>Ofrecer soluciones de software, análisis de datos y diseño gráfico de alta calidad para satisfacer las necesidades de nuestros clientes y ayudar a las empresas a prosperar.</p>
                  </div>
              </div>
          </div>
          <div class="flip-container">
              <div class="flipper">
                  <div class="front">
                      Visión
                      <div class="symbol">↻</div>
                  </div>
                  <div class ="back">
                      <img class="icon" src="pngegg (8).png" alt="Icono de Visión" width="55" height="55">
                      <p>Ser líder global en desarrollo de software, análisis de datos y diseño gráfico, destacando por nuestra innovación y compromiso con la satisfacción del cliente.</p>
                  </div>
              </div>
          </div>
          <div class="flip-container">
              <div class="flipper">
                  <div class="front">
                      Valores
                      <div class="symbol">↻</div>
                  </div>
                  <div class="back">
                      <img class="icon" src="Valores.png" alt="Icono de Valores" width="55" height="55">
                      <ul>
                          <li>Excelencia.</li>
                          <li>Innovación.</li>
                          <li>Compromiso total.</li>
                          <li>Colaboración.</li>
                          <li>Aprendizaje Continuo.</li>
                          <li>Ética y Responsabilidad.</li>
                      </ul>    
                  </div>
              </div>
          </div>
      </div>
  
      <script>
          const flipContainers = document.querySelectorAll('.flip-container');
  
          flipContainers.forEach(container => {
              container.addEventListener('click', () => {
                  container.classList.toggle('hover');
              });
          });
      </script>
  </body>
  </html>
  
  <section id="desarrollo-software">
    <h2>Desarrollo de Software</h2>
    <p>InnoFusion Studios nos dedicamos a crear software personalizado que permite dar vida a las ideas y proyectos digitales. Esto implica el diseño, la codificación y la implementación de aplicaciones y programas informáticos que satisfacen las necesidades específicas de cada cliente.</p>
    <p>Nuestro lema <b>"Creamos código que da vida a tus sueños digitales"</b> refleja nuestro compromiso de convertir conceptos y sueños en aplicaciones y sistemas funcionales. Contamos con un equipo de desarrollo que se enfoca en la innovación y la calidad para garantizar que las soluciones que entregan sean efectivas y eficientes.</p>
</section>

<section id="diseno-grafico">
    <h2>Diseño Gráfico</h2>
    <p>InnoFusion Studios ofrecemos servicios de diseño gráfico, lo que implica la creación de elementos visuales impresionantes que van desde logotipos, gráficos, ilustraciones, hasta diseños de sitios web y aplicaciones.</p>
    <p>Nuestro lema <b>"Transformamos ideas en imágenes asombrosas"</b> destaca nuestra capacidad para dar vida a la visión y conceptos de nuestros clientes a través de la creatividad visual. Nuestro equipo de diseñadores se dedica a la estética, la usabilidad y la coherencia visual para crear una impresión duradera.</p>
</section>

<section id="analisis-datos">
    <h2>Análisis de Datos</h2>
    <p>Nos especializamos en la interpretación de datos para extraer información valiosa y significativa. Esto puede incluir la recopilación, procesamiento y análisis de datos de diversas fuentes para ayudar a los clientes a tomar decisiones informadas.</p>
    <p>Nuestro lema <b>"Convertimos números en información valiosa"</b> resalta nuestro enfoque en la transformación de datos en conocimiento útil. Los expertos en análisis de datos de InnoFusion Studios ayudan a nuestros clientes a descubrir tendencias, patrones y oportunidades ocultas en los datos.</p>
</section>
     <section>
        <h2>Síguenos en Redes Sociales:</h2>
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
            <link rel="stylesheet" href="./style.css">
            <title>Redes Sociales</title>
            <style>
                .icons {
                    display: flex;
                }
                .icon {
                    margin: 10px;
                }
                .icon i {
                    font-size: 30px;
                    cursor: pointer;
                }
                .icon i:hover {
                    color: #000;
                }
            </style>
        </head>
        <body>
            <footer class="wrapper">
                <div class="icons">
                    <div class="icon">
                        <a href="https://www.facebook.com/profile.php?id=61552425702550" target="_blank">
                            <i class="fab fa-facebook" style="color: #1877f2;"></i>
                        </a>
                    </div>
                    <div class="icon">
                        <a href="https://www.instagram.com/innofusionstudios/" target="_blank">
                            <i class="fab fa-instagram" style="color: #e4405f;"></i>
                        </a>
                    </div>
                    <div class="icon">
                        <a href="https://twitter.com/InnofusionS" target="_blank">
                            <i class="fab fa-twitter" style="color: #1da1f2;"></i>
                        </a>
                    </div>
                    <div class="icon">
                        <a href="https://youtube.com/@InnofusionStudios?si=3ODYuxWjUoxh7JF8" target="_blank">
                            <i class="fab fa-youtube" style="color: #c4302b;"></i>
                        </a>
                    </div>
                    <div class="icon">
                        <a href="https://www.linkedin.com/in/innofusion-studios-3015a6297/" target="_blank">
                            <i class="fab fa-linkedin" style="color: #0077b5;"></i>
                        </a>
                    </div>
                    </div>
                </div>
            </footer>
        </body>
        </html>
    </section>
    
    <script>
        function openMenu() {
            document.getElementById("menu").style.width = "250px";
        }

        function closeMenu() {
            document.getElementById("menu").style.width = "0";
        }
    </script>
</body>
</html>
