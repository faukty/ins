
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#10243b">
  <meta name="description" content="Sitio oficial del Colegio Santa Isabel de Hungría. Conocé nuestra institución, niveles educativos, novedades y formas de contacto.">
  <title>Inicio | Colegio Santa Isabel de Hungría</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>
<body>

  <!-- ENCABEZADO -->
  <header class="encabezado">
    <a class="marca" href="index.html" aria-label="Ir al inicio">
      <img class="escudo" src="logo.png" alt="Escudo del Colegio Santa Isabel de Hungría">
      <span class="marca-texto">
        <strong>Colegio Santa Isabel de Hungría</strong>
        <small>Educación y formación integral</small>
      </span>
    </a>

    <button class="menu-toggle" type="button"
      aria-label="Abrir menú" aria-expanded="false"
      aria-controls="menu-principal">
      <span></span><span></span><span></span>
    </button>

    <nav class="menu" id="menu-principal" aria-label="Navegación principal">
      <a class="activo" aria-current="page" href="index.html">Inicio</a>
      <a href="institucion.html">La institución</a>
      <a href="niveles.html">Niveles</a>
      <a href="noticias.html">Novedades</a>
      <a href="contacto.html">Contacto</a>
    </nav>
  </header>

  <main>
    <!-- PORTADA CON VIDEO -->
    <section class="portada">
      <video class="video-fondo"
        autoplay muted loop playsinline
        poster="portada.jpg"
        aria-hidden="true">
        <source src="video-colegio.mp4" type="video/mp4">
      </video>

      <div class="portada-capa"></div>

      <div class="portada-contenido revelar">
        <span class="etiqueta">COLEGIO SANTA ISABEL DE HUNGRÍA</span>
        <h1>Un lugar para aprender, crecer y construir el futuro</h1>
        <p>
          Te damos la bienvenida a nuestro espacio institucional.
          Descubrí nuestra propuesta educativa y nuestra comunidad.
        </p>

        <div class="botones-portada">
          <a class="boton boton-dorado" href="institucion.html">
            Conocé el colegio
          </a>
          <a class="boton boton-transparente" href="niveles.html">
            Nuestros niveles
          </a>
        </div>
      </div>

      <a class="indicador-scroll" href="#bienvenida">
        Descubrí más <span aria-hidden="true">↓</span>
      </a>
    </section>

    <!-- BIENVENIDA -->
    <section class="seccion bienvenida revelar" id="bienvenida">
      <div class="seccion-titulo">
        <span class="etiqueta etiqueta-oscura">NUESTRA COMUNIDAD</span>
        <h2>Bienvenidos a nuestro colegio</h2>
        <p>
          Un espacio para acompañar el aprendizaje, fortalecer los valores
          y promover el desarrollo integral de cada estudiante.
        </p>
      </div>
    </section>

    <!-- ACCESOS A LOS APARTADOS -->
    <section class="seccion seccion-tarjetas">
      <div class="seccion-titulo revelar">
        <span class="etiqueta etiqueta-oscura">EXPLORÁ</span>
        <h2>Conocé nuestra institución</h2>
        <p>Encontrá la información que necesitás en nuestros apartados.</p>
      </div>

      <div class="tarjetas">
        <a class="tarjeta revelar" href="institucion.html">
          <div class="tarjeta-icono" aria-hidden="true">⛪</div>
          <h3>La institución</h3>
          <p>Conocé nuestra historia, identidad y comunidad educativa.</p>
          <span class="tarjeta-enlace">Conocer más →</span>
        </a>

        <a class="tarjeta revelar" href="niveles.html">
          <div class="tarjeta-icono" aria-hidden="true">🎓</div>
          <h3>Niveles educativos</h3>
          <p>Descubrí nuestra propuesta y los niveles que ofrecemos.</p>
          <span class="tarjeta-enlace">Ver niveles →</span>
        </a>

        <a class="tarjeta revelar" href="noticias.html">
          <div class="tarjeta-icono" aria-hidden="true">📢</div>
          <h3>Novedades</h3>
          <p>Consultá noticias, actividades y acontecimientos escolares.</p>
          <span class="tarjeta-enlace">Ver novedades →</span>
        </a>

        <a class="tarjeta revelar" href="contacto.html">
          <div class="tarjeta-icono" aria-hidden="true">📲</div>
          <h3>Contacto</h3>
          <p>Encontrá los medios para comunicarte con el colegio.</p>
          <span class="tarjeta-enlace">Contactarnos →</span>
        </a>
      </div>
    </section>

    <!-- FRANJA DESTACADA -->
    <section class="franja revelar">
      <div>
        <span class="etiqueta">ESTAMOS PARA ACOMPAÑARTE</span>
        <h2>¿Querés conocer más sobre el colegio?</h2>
        <p>Escribinos o consultá las novedades de nuestra comunidad.</p>
      </div>
      <a class="boton boton-dorado"
        href="contacto.html">Ponete en contacto</a>
    </section>

    <!-- GALERÍA -->
    <section class="seccion">
      <div class="seccion-titulo revelar">
        <span class="etiqueta etiqueta-oscura">NUESTRO DÍA A DÍA</span>
        <h2>Momentos de nuestra comunidad</h2>
        <p>Un espacio para compartir imágenes de la vida escolar.</p>
      </div>

      <div class="galeria">
        <button class="foto-galeria revelar" type="button"
          data-imagen="imagenes/colegio.jpg"
          data-descripcion="Nuestro colegio"
          aria-label="Ampliar fotografía del colegio">
          <img src="colegio.jpg" alt="Instalaciones del colegio"
            loading="lazy">
          <span>Nuestro colegio ↗</span>
        </button>

        <button class="foto-galeria revelar" type="button"
          data-imagen="imagenes/alumnos.jpg"
          data-descripcion="Nuestra comunidad educativa"
          aria-label="Ampliar fotografía de la comunidad educativa">
          <img src="images.jpg" alt="Comunidad educativa"
            loading="lazy">
          <span>Nuestra comunidad ↗</span>
        </button>

        <button class="foto-galeria revelar" type="button"
          data-imagen="imagenes/actividades.jpg"
          data-descripcion="Actividades escolares"
          aria-label="Ampliar fotografía de actividades escolares">
          <img src="act.jpg" alt="Actividades escolares"
            loading="lazy">
          <span>Actividades ↗</span>
        </button>
      </div>
    </section>
  </main>

  <!-- PIE INSTITUCIONAL -->
  <footer class="pie">
    <div class="pie-contenido">
      <a class="marca marca-pie" href="index.html">
        <img class="escudo" src="logo.png"
          alt="Escudo del Colegio Santa Isabel de Hungría" loading="lazy">
        <span class="marca-texto">
          <strong>Colegio Santa Isabel de Hungría</strong>
          <small>Educación y formación integral</small>
        </span>
      </a>

      <div class="pie-enlaces">
        <h3>Explorá</h3>
        <a href="institucion.html">La institución</a>
        <a href="niveles.html">Niveles educativos</a>
        <a href="noticias.html">Novedades</a>
        <a href="contacto.html">Contacto</a>
      </div>

      <div class="pie-redes">
        <h3>Seguinos</h3>
        <!-- Reemplazá estos enlaces por las cuentas oficiales -->
        <a href="https://www.instagram.com/"
          target="_blank" rel="noopener noreferrer">Instagram ↗</a>
        <a href="https://www.facebook.com/"
          target="_blank" rel="noopener noreferrer">Facebook ↗</a>
        <a href="https://www.youtube.com/"
          target="_blank" rel="noopener noreferrer">YouTube ↗</a>
      </div>
    </div>

    <div class="pie-final">
      <p>© <span class="anio-actual"></span> Colegio Santa Isabel de Hungría.</p>
      <p>Todos los derechos reservados.</p>
    </div>
  </footer>

  <!-- BOTÓN VOLVER ARRIBA -->
  <button class="volver-arriba" type="button"
    aria-label="Volver al inicio" title="Volver arriba">↑</button>

  <!-- BOTÓN Y VENTANA DEL CHATBOT -->
  <button class="chatbot-toggle" type="button"
    aria-label="Abrir asistente virtual"
    aria-expanded="false" aria-controls="chatbot-panel">
    <span aria-hidden="true">✦</span>
    <span class="chatbot-texto">¿Necesitás ayuda?</span>
  </button>

  <section class="chatbot-panel" id="chatbot-panel"
    aria-label="Asistente virtual" hidden>
    <div class="chatbot-cabecera">
      <div>
        <strong>Asistente del colegio</strong>
        <small>Consultas frecuentes</small>
      </div>
      <button class="chatbot-cerrar" type="button"
        aria-label="Cerrar asistente">×</button>
    </div>

    <div class="chatbot-mensajes" aria-live="polite">
      <p class="mensaje mensaje-bot">
        ¡Hola! 👋 Soy el asistente virtual del colegio.
        ¿Sobre qué te gustaría consultar?
      </p>
    </div>

    <div class="chatbot-opciones">
      <button type="button" data-pregunta="inscripciones">
        Inscripciones
      </button>
      <button type="button" data-pregunta="niveles">
        Niveles educativos
      </button>
      <button type="button" data-pregunta="horarios">
        Horarios
      </button>
      <button type="button" data-pregunta="contacto">
        Contacto
      </button>
    </div>

    <form class="chatbot-form">
      <label class="solo-lectores" for="chatbot-input">
        Escribí tu consulta
      </label>
      <input id="chatbot-input" name="consulta"
        type="text" maxlength="300"
        placeholder="Escribí tu consulta..."
        autocomplete="off" required>
      <button type="submit" aria-label="Enviar consulta">➤</button>
    </form>
    <p class="chatbot-aviso">Asistente automático de consultas frecuentes.</p>
  </section>

  <!-- GALERÍA AMPLIABLE -->
  <dialog class="visor-imagen" aria-label="Fotografía ampliada">
    <button class="visor-cerrar" type="button"
      aria-label="Cerrar fotografía">×</button>
    <img src="" alt="">
    <p></p>
  </dialog>

  <!-- WHATSAPP -->
  <a class="whatsapp-flotante"
    href="https://wa.me/549XXXXXXXXXX"
    target="_blank" rel="noopener noreferrer"
    aria-label="Contactar al colegio por WhatsApp"
    title="Contactanos por WhatsApp">
    <svg viewBox="0 0 32 32" aria-hidden="true">
      <path fill="currentColor"
        d="M16 3a12.7 12.7 0 0 0-10.9 19.2L3.5 29l7-1.8A12.8 12.8 0 1 0 16 3Zm0 23.2a10.4 10.4 0 0 1-5.3-1.5l-.4-.2-4.1 1.1 1.1-4-.3-.4A10.4 10.4 0 1 1 16 26.2Zm5.7-7.8c-.3-.2-1.8-.9-2.1-1s-.5-.2-.7.2-.8 1-1 1.2-.4.2-.7.1a8.5 8.5 0 0 1-2.5-1.5 9.4 9.4 0 0 1-1.7-2.1c-.2-.4 0-.5.1-.7l.5-.6c.2-.2.2-.4.3-.6s0-.4 0-.6-.7-1.7-1-2.3c-.2-.6-.5-.5-.7-.5h-.6c-.2 0-.6.1-.9.4s-1.2 1.2-1.2 2.8 1.2 3.2 1.4 3.4 2.4 3.7 5.8 5.1c.8.4 1.5.6 2 .7.9.3 1.7.2 2.3.1.7-.1 1.8-.7 2-1.4.2-.7.2-1.3.1-1.4s-.4-.3-.7-.5Z"/>
    </svg>
  </a>

</body>
</html>
