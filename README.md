<!DOCTYPE html><html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portafolio de Daruki</title>
    <style>
      :root {
        --bg-dark: #0d1117;
        --bg-light: #161b22;
        --accent: #3b82f6;
        --text: #e5e7eb;
        --text-secondary: #9ca3af;
        --radius: 12px;
      }* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }

  body {
    background: var(--bg-dark);
    color: var(--text);
    line-height: 1.6;
  }

  header {
    background: linear-gradient(135deg, #1d4ed8 0%, #3b82f6 50%, #60a5fa 100%);
    padding: 2rem 1rem 5rem;
    text-align: center;
  }

  header h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
  }

  header p {
    font-size: 1.1rem;
    color: #f3f4f6;
  }

  nav {
    position: sticky;
    top: 0;
    background: var(--bg-light);
    padding: 0.75rem 1rem;
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
    z-index: 100;
  }

  nav a {
    color: var(--text);
    text-decoration: none;
    font-weight: 600;
    transition: color 0.2s ease-in-out;
  }

  nav a:hover {
    color: var(--accent);
  }

  section {
    padding: 4rem 1rem;
    max-width: 900px;
    margin: 0 auto;
  }

  section h2 {
    font-size: 1.75rem;
    margin-bottom: 1rem;
  }

  /* Timeline styles */
  .timeline {
    position: relative;
    margin-left: 1rem;
    padding-left: 1rem;
    border-left: 2px solid var(--accent);
  }

  .timeline-item {
    margin-bottom: 2rem;
    position: relative;
    display: flex;
    align-items: flex-start;
    gap: 1rem;
  }

  .timeline-item::before {
    content: "";
    position: absolute;
    left: -11px;
    top: 4px;
    width: 14px;
    height: 14px;
    background: var(--accent);
    border-radius: 50%;
  }

  .timeline-item h3 {
    font-size: 1.25rem;
    margin-bottom: 0.25rem;
  }

  .timeline-item p {
    color: var(--text-secondary);
  }

  .project-logo {
    width: 64px;
    height: auto;
    border-radius: var(--radius);
    object-fit: cover;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
  }

  /* Gallery */
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
  }

  .gallery img {
    width: 100%;
    border-radius: var(--radius);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s ease-in-out;
  }

  .gallery img:hover {
    transform: scale(1.05);
  }

  footer {
    background: var(--bg-light);
    text-align: center;
    padding: 2rem 1rem;
  }

  footer a {
    color: var(--accent);
    text-decoration: none;
  }
</style>

  </head>
  <body>
    <header>
      <h1>Daruki</h1>
      <p>Configurator, Streamer &amp; Minecraft Server Developer</p>
    </header><nav>
  <a href="#historia">Historia</a>
  <a href="#proyectos">Proyectos</a>
  <a href="#galeria">Galería de Configs</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="historia">
  <h2>Mi Historia</h2>
  <p>
    Todo empezó en el verano de 2022 investigando cómo crear un servidor de
    Minecraft para jugar con mis amigos. Desde un humilde mundo en Aternos
    hasta administrar redes con decenas de jugadores, he aprendido a
    configurar, optimizar y liderar proyectos que ponen la experiencia de
    la comunidad en primer lugar.fileciteturn1file0
  </p>
</section>

<section id="proyectos">
  <h2>Principales Proyectos</h2>
  <div class="timeline">
    <div class="timeline-item">
      <img src="nuevaland_logo.png" alt="Logo NuevaLand" class="project-logo" />
      <div>
        <h3>NuevaLand (2022)</h3>
        <p>Mi primer servidor Java, con tienda online básica y configuraciones sencillas.</p>
      </div>
    </div>
    <div class="timeline-item">
      <img src="turipland_logo.png" alt="Logo TuripLand / SoulMC" class="project-logo" />
      <div>
        <h3>TuripLand / SoulMC (2022)</h3>
        <p>Mejoras notorias, equipo ampliado y una media de 10 jugadores concurrentes.</p>
      </div>
    </div>
    <div class="timeline-item">
      <img src="muntbox_logo.png" alt="Logo MuntBox" class="project-logo" />
      <div>
        <h3>MuntBox (2023)</h3>
        <p>Servidor profesional donde ascendí a co‑owner gestionando 10‑15 jugadores.</p>
      </div>
    </div>
    <div class="timeline-item">
      <img src="minelive_logo.png" alt="Logo MineLive" class="project-logo" />
      <div>
        <h3>MineLive (2023)</h3>
        <p>Soporte y operador de confianza en una comunidad de 40‑50 jugadores.</p>
      </div>
    </div>
    <div class="timeline-item">
      <img src="hypexmc_logo.png" alt="Logo HypexMC" class="project-logo" />
      <div>
        <h3>HypexMC (2024)</h3>
        <p>Sistemas únicos como tradeos y puertas automáticas; alcanzamos 40‑50 jugadores.</p>
      </div>
    </div>
    <div class="timeline-item">
      <img src="spacemc_logo.png" alt="Logo SpaceMC" class="project-logo" />
      <div>
        <h3>SpaceMC (2024)</h3>
        <p>Configurator en una network de 60‑70 jugadores con picos de 100+.</p>
      </div>
    </div>
    <div class="timeline-item">
      <img src="solarmc_logo.png" alt="Logo SolarMC" class="project-logo" />
      <div>
        <h3>SolarMC (2025‑Actualidad)</h3>
        <p>Proyecto actual con configuraciones nunca vistas, enfocado en innovación.</p>
      </div>
    </div>
  </div>
</section>

<section id="galeria">
  <h2>Galería de Configs</h2>
  <p>Imágenes de menús, HUDs y carteles en juego:</p>
  <div class="gallery">
    <img src="menu.png" alt="Menú personalizado de SolarMC" />
    <img src="koth.png" alt="Cartel KOTH con recompensas" />
  </div>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>
    ¿Te interesa llevar tu servidor al siguiente nivel? Contáctame a través de
    <a href="https://tiktok.com/@daruki_dolarmc" target="_blank" rel="noopener">@daruki_dolarmc</a>
    o envíame un mensaje directo en Discord (<strong>Daruki#1234</strong>).
  </p>
</section>

<footer>
  <p>&copy; 2025 Daruki — Todos los derechos reservados.</p>
</footer>

  </body>
</html># Portafolio-Daruki
