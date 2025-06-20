<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>InterConecta S.A. | Rediseño Organizacional</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Inter', sans-serif;
      background-color: #f4f7fa;
      color: #333;
      line-height: 1.6;
      scroll-behavior: smooth;
    }
    header {
      background: linear-gradient(135deg, #003366, #005999);
      color: #fff;
      padding: 3rem 1.5rem;
      text-align: center;
      position: relative;
    }
    header img.logo {
      width: 100px;
      position: absolute;
      top: 1rem;
      left: 1rem;
    }
    nav {
      background: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      display: flex;
      justify-content: center;
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #003366;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #0070f3;
    }
    .container {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 0 1.5rem;
    }
    section {
      margin-bottom: 3rem;
      animation: fadeIn 1s ease-in;
    }
    h2 {
      color: #003366;
      margin-bottom: 1rem;
    }
    ul { padding-left: 1.5rem; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: #fff;
      border-radius: 8px;
      padding: 1.5rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
      border-left: 5px solid #0070f3;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.12);
    }
    .card h3 {
      color: #005999;
      margin-bottom: 0.5rem;
    }
    .card i {
      font-size: 1.5rem;
      color: #005999;
      margin-right: 0.5rem;
    }
    footer {
      background: #003366;
      color: #fff;
      text-align: center;
      padding: 2rem 1.5rem;
      margin-top: 4rem;
    }
    form {
      background: #fff;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    form input, form textarea, form select {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #0070f3;
      color: #fff;
      border: none;
      padding: 0.75rem 1.5rem;
      font-weight: 600;
      cursor: pointer;
      border-radius: 4px;
      transition: background 0.3s ease;
    }
    form button:hover {
      background-color: #005ac1;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Telecommunication_icon.svg/512px-Telecommunication_icon.svg.png" alt="Logo InterConecta" class="logo">
    <h1>InterConecta S.A.</h1>
    <p>Reconstruyendo la confianza con innovación organizacional</p>
  </header>

  <nav>
    <a href="#contexto">Contexto</a>
    <a href="#estructura">Estructura CCI</a>
    <a href="#conecta360">Conecta360</a>
    <a href="#feedback">Feedback</a>
    <a href="#reconocimiento">Reconocimiento</a>
    <a href="#encuesta">Encuesta</a>
    <a href="#conclusion">Conclusión</a>
  </nav>

  <main class="container">
    <section id="contexto">
      <h2><i class="fas fa-building"></i> Contexto Organizacional</h2>
      <p>Tras años de crecimiento y cambios impulsados por la pandemia, InterConecta S.A. enfrentó una crisis de confianza interna...</p>
    </section>

    <!-- Secciones previas aquí (omitidas por brevedad) -->

    <section id="feedback">
      <h2><i class="fas fa-comment-dots"></i> Envíanos tu Retroalimentación</h2>
      <form onsubmit="alert('Gracias por tu mensaje. ¡Será tenido en cuenta!'); return false;">
        <input type="text" placeholder="Nombre (opcional)">
        <textarea rows="5" placeholder="Escribe aquí tus ideas o inquietudes"></textarea>
        <button type="submit">Enviar</button>
      </form>
    </section>

    <section id="reconocimiento">
      <h2><i class="fas fa-star"></i> Reconoce a un Compañero</h2>
      <form onsubmit="alert('Reconocimiento enviado con éxito'); return false;">
        <input type="text" placeholder="Nombre del colaborador">
        <textarea rows="4" placeholder="Motivo del reconocimiento"></textarea>
        <button type="submit">Reconocer</button>
      </form>
    </section>

    <section id="encuesta">
      <h2><i class="fas fa-chart-pie"></i> Encuesta de Clima Organizacional</h2>
      <form onsubmit="alert('Gracias por participar'); return false;">
        <label>¿Te sientes valorado en tu equipo?</label>
        <select>
          <option>Siempre</option>
          <option>A veces</option>
          <option>Nunca</option>
        </select>
        <label>¿Qué mejorarías en la comunicación interna?</label>
        <textarea rows="3"></textarea>
        <button type="submit">Enviar Encuesta</button>
      </form>
    </section>

    <section id="conclusion">
      <h2><i class="fas fa-check-circle"></i> Conclusión</h2>
      <p>Con estas herramientas, InterConecta S.A. activa canales reales para la participación, el reconocimiento y la mejora continua...</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 InterConecta S.A. | Rediseño Organizacional</p>
  </footer>
</body>
</html>
# Hi there 👋

<!--
**interconecta-web/Interconecta-web** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
