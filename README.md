<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <title>Portafolio</title>
    <link rel="stylesheet" href="./estilo.css">
</head>
<body>
    <div class="container-header">
        <header>
            <div class="logo">
                <a href="#">AZ</a>
            </div>
            <nav id="nav">
                <ul>
                    <li><a href="#inicio" onclick="seleccionar()">Inicio</a></li>
                    <li><a href="#sobremi" onclick="seleccionar()">Sobre mi</a></li>
                    <li><a href="#skills"onclick="seleccionar()">Skills</a></li>
                    <li><a href="#curriculum"onclick="seleccionar()">Curriculum</a></li>
                    <li><a href="#portafolio"onclick="seleccionar()">Portafolio</a></li>
                    <li><a href="#contacto"onclick="seleccionar()">Contacto</a></li>
                </ul>
            </nav>
            <div class="nav-esponsive" onclick="mostrarOcultaMenu()">
                <i class="fa-solid fa-bars"></i>
            </div>
        </header>
    </div>

    <section id="inicio" class="inicio">
        <div class="contenido-banner">
            <div class="contenido-img">
                <img src="img/kjw8_3LEScGYAY_70TahCA.jfif" class="circulo" alt="">
            </div>
            <h1>ANDRÉS ZARAGOZA</h1>
            <h2>Ingeniero y Pogramador </h2>
            <div class="redes">
                <a href="https://www.tiktok.com/@elmaracucho007" target="_blank"><i class="fa-brands fa-tiktok"></i></a>
                <a href="https://www.linkedin.com/in/andres-miguel-zaragoza-quintero-bb869a123/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
                <a href="https://github.com/andreszaragoza" target="_blank"><i class="fa-brands fa-github"></i></a>
            </div>
        </div>
    </section>

    <section id="sobremi" class="sobremi">
        <div class="contenido-seccion">
            <h2>Sobre mi</h2>
            <p><span>Hola, soy Andrés Zaragoza.</span>
            Desarrollador en transición a Data Scientist, apasionado y con experiencia en HTML, CSS, JavaScript, Angular, he completado varios proyectos independientes, incluyendo diseño de páginas web y creación de videojuegos con Pygame, con una base sólida en ingeniería industrial, aporto una perspectiva única y habilidades de resolución de problemas a mis proyectos de programación. Actualmente, estoy cursando un certificado en Data Science para fortalecer mis conocimientos y explorar nuevas oportunidades en el análisis y la ciencia de datos.</p>

            <div class="fila">
                <div class="col">
                    <h3>Datos Personales</h3>
                    <ul>
                        <li>
                            <strong>Cumpleaños</strong>
                            29-12-1993
                        </li>
                        <li>
                            <strong>Teléfono</strong>
                            695-96-60-86
                        </li>
                        <li>
                            <strong>Email</strong>
                            zaragozaquintero@gmail.com
                        </li>
                        <li>
                            <strong>Dirección</strong>
                            Madrid , España
                        </li>
                        <li>
                            <strong>Cargo</strong>
                            Freenlance
                        </li>
                    </ul>
                </div>

                <div class="col">
                    <h3>Intereses</h3>
                    <div class="contenedor-intereses">
                        <div class="interes">
                            <i class="fa-solid fa-gamepad"></i>
                            <span>Videojuegos</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-video"></i>
                            <span>Edición</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-futbol"></i>
                            <span>Deporte</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-music"></i>
                            <span>Musica</span>
                        </div>
                    </div>
                </div>
            </div>
            <button>
                <a download="Cv de Andres Zaragoza" href="./Currículum Profesional  de Andres Zaragoza.pdf">Descargar CV</a><i class="fa-solid fa-download"></i>
                <span class="overlay"></span>
            </button>
        </div>
    </section>

    <section class="skills" id="skills">
        <div class="contenido-seccion">
            <h2>Skills</h2>
            <div class="fila">
                <div class="col">
                    <h3>Technical Skills</h3>
                    <div class="skill">
                        <span>Javascript</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>HTML & CSS</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Python</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>SQL</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Capcut</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Angular</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <h3>Profesional Skills</h3>
                    <div class="skill">
                        <span>Comunicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Trabajo en Equipo</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Creatividad</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Dedicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span></span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="curriculum" id="curriculum">
        <div class="contenido-seccion">
            <h2>Curriculum</h2>
            <div class="fila">
                <div class="col-izquierda">
                    <h3>Educación</h3>
                    <div class="item izq">
                        <h4>Data Sciencist</h4>
                        <span class="casa">The Bridge</span>
                        <span class="fecha">2024-2025</span>
                        <p> Python aplicada a Data y a extraer, transformar y analizar los datos con las últimas tendencias en inteligencia artificial.</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <div class="item izq">
                        <h4>Front end Developer</h4>
                        <span class="casa">Openbootcamp</span>
                        <span class="fecha">2023-2024</span>
                        <p>Aprendizaje intensivo de HTML, CSS y JavaScript con
                            desarrollo de interfaces de usuario interactivas y responsive utilizando angular y
                            práctica en desarrollo de aplicaciones web completas, desde la estructura y el diseño hasta la implementación de funcionalidades front-end.</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                    </div>
                    </div>
                    <div class="item izq">
                        <h4>Ingenieria Industrial</h4>
                        <span class="casa">Universidad Rafael Belloso Chacin</span>
                        <span class="fecha">2011-2015</span>
                        <p>disciplina con una visión muy amplia y que está relacionada con el diseño, mejoramiento, instalación y manejo de sistemas integrados por gente, materiales y equipos para toda clase de productos o servicios.</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                </div>
                <div class="col-derecha">
                    <h3>Experiencia</h3>
                    <div class="item der">
                        <h4>Front End Developer</h4>
                        <span class="casa">Freelance</span>
                        <span class="fecha">2022</span>
                        <p>-Descripción: Creación de un formulario de contacto y registro completamente
                            responsivo.</p>
                        <p>-Implementación de animaciones suaves para una mejor experiencia de usuario.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Python</h4>
                        <span class="casa">Freelance</span>
                        <span class="fecha">2023</span>
                        <p>-Desarrollo de un videojuego con Pygame, incluyendo creación de pantalla de juego,
                            personajes y asignación de movimientos, sonidos y efectos.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Developer Web</h4>
                        <span class="casa">Freelance</span>
                        <span class="fecha">2023</span>
                        <p>-Descripción: Desarrollo de una aplicación web para la gestión de tareas que
                            permite a los usuarios agregar, editar, eliminar y marcar tareas como completadas.</p>
                        <p>-Implementación de animaciones y transiciones para una experiencia de usuario fluida y
                            optimización del sitio para mejorar el rendimiento y la velocidad de carga.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    </div>
            </div>
            </div>
        </div>
    </section>

    <section id="portafolio" class="portafolio">
        <div class="contenido-seccion">
            <h2>Portafolio</h2>
            <div class="galeria">
                <div class="proyecto">
                    <img src="./img/Crea-una-página-web-3.png" alt="">
                    <div class="overlay">
                        <h3>Formulario</h3>
                        <p>Animado</p>
                        <a href="https://github.com/andreszaragoza/Formulario-animado"><i class="fa-brands fa-github"></i></a>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="./img/Coinbase.png" alt="">
                    <div class="overlay">
                        <h3>Coinbase </h3>
                        <p>Maqueta</p>
                        <a href="https://github.com/andreszaragoza/14-15-Proyecto/tree/main"><i class="fa-brands fa-github"></i></a>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="./img/Invasion Espacial.png" alt="">
                    <div class="overlay">
                        <h3>Invasion Espacial</h3>
                        <p>Pygame</p>
                        <a href="https://github.com/andreszaragoza/Pygame"><i class="fa-brands fa-github"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contacto" class="contacto">
        <div class="contenido-seccion">
            <h2>CONTACTO</h2>
            <div class="fila">
                <div class="col">
                    <form action="https://formsubmit.co/zaragozaquintero@gmail.com" method="POST" />
                    <input type="text" name="name" required placeholder="Tu Nombre">
                    <input type="email" name="email" required placeholder="Correo">
                    <textarea name="Mensaje" id="" cols="30" rows="10" placeholder="Mensaje"></textarea>
                    <button>
                        Enviar Mensaje<i class="fa-solid fa-paper-plane"></i>
                        <span class="overlay"></span>
                    </button>
                </form>
                </div>
            </div>
    
    
    <script src="./script.js"></script>
</body>
</html>
